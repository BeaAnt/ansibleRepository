# ansibleRepository   
A repository created to learn Ansible   

## installing Ansible    
`sudo apt update`   
`sudo apt install ansible`    

## configuring Inventory File (hosts)    
`cd /etc/ansible`   
`sudo nano hosts`   

add a group of nodes for manage in the script:    

[nomegruppo]    
host1 ansible_ssh_host=(IPaddress) ansible_user=(user) ansible_ssh_private_key_file=(path_key)    

## connecting test    
`ansible -m ping`(nomegruppo)   

## creating Playbook    
create a folder for playbooks:    
`cd /etc/ansible`   
`mkdir playbook`    

write a playbook:   
`cd playbook`   
nano playbook1.yaml




