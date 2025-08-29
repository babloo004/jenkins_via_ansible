<<<<<<< HEAD
### setup jenkins in your servers
### edit the inventory file
### add centos machines under centos group and ubuntu machines in ubuntu group
## install jenkins
- ansible-playbook -i inventory main.yaml

## remove jenkins (not java)
- ansible-playbook -i inventory.yaml remove.yaml

## setup jenkins directpry ifor agent setup
- ansible-playbook -i inventory.yaml agent.yaml
=======
# jenkins_via_ansible
>>>>>>> e152d88d557d90b477278fdba2aba45e0b2493f9
