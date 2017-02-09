# playbooks

My workstation setup.

##First install Git and Ansible:
```
$ sudo apt install git
$ sudo apt install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt update
$ sudo apt install ansible
```

##Then download this repo and run:
```
$ ansible-galaxy install -r requirements.yml
$ ansible-playbook playbooks/bootstrap-my-station.yml
```
