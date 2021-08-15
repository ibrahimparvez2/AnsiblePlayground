# AnsiblePlayground

some patches for working on linux:

 sudo cp $(which ansible) /usr/bin
 sudo cp $(which ansible-playbook) /usr/bin


 ansible-playbook playbook.yml -user=docker
 or sudo ansible-playbook  playbook.yml

playbook will update hosts ```[containers]``` with ip dynamically

now run against other playbooks example ```vault.yml``` 
````---
  - hosts: containers
  ```
  