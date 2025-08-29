### setup jenkins in your servers
### edit the inventory file
### add centos machines under centos group and ubuntu machines in ubuntu group
## install jenkins
- ansible-playbook -i inventory playbooks/jenkins/setup.yaml

## remove jenkins (not java)
- ansible-playbook -i inventory.yaml playbooks/jenkins/remove.yaml

## setup jenkins directpry ifor agent setup
- ansible-playbook -i inventory.yaml playbooks/jenkins/agent.yaml

## setup nexus(RedHat)
- ansible-playbook -i inventory.yaml playbooks/nexus/nexus.yaml
