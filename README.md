# playbooks

My workstation setup.

First install Ansible:
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible

Then download this repo and run:
$ ansible-galaxy install -r requirements.yml
$ ansible-playbook playbooks/ohmyzsh.yml
