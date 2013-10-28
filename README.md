Restore My Ubuntu PC
-------------

Installed Ubuntu 12.04.3 onto my Lenovo S431 Laptop. 
Want to learn Ansible

Using ansible to backup the config of my laptop. 

After installing Ubuntu 12.04 run the following

```
# sudo apt-get install python-pip
# sudo pip install ansible
# cat "127.0.0.1" > ~/ansible_hosts
# export ANSIBLE_HOSTS=$HOME/ansible_hosts
# cd restore_pc
# ansible-playbook site.yml -K

```
