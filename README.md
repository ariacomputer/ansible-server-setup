# ansible-server-setup
Ansible server setup

To run, originally specifying a sudo password: 

    git clone https://github.com/ariacomputer/ansible-server-setup
    ansible-playbook site.yml -i hosts -u aria -kK

Afterward:

    ansible-playbook site.yml -i hosts -u ariacomputer