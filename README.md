# Ansible
## using community general
### commands
### 1 - Launch playbook
* ansible-playbook -i hosts apache.yml
### 2 - Delete playbook
* ansible nodes -i hosts -m apt -a "name=apache state=absent"
