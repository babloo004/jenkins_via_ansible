### setup jenkins in your servers
### edit the inventory file
### add centos machines under centos group and ubuntu machines in ubuntu group
## install jenkins
- ansible-playbook -i inventory main.yaml

## remove jenkins (not java)
- ansible-playbook -i inventory.yaml remove.yaml
