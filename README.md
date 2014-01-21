Restore My Ubuntu PC
-------------

Installed Ubuntu 12.04.3 onto my Lenovo S431 Laptop. 

Using ansible to backup the config of my laptop. 

After installing Ubuntu 12.04 run the following to restore my laptop.

```
# sudo apt-get install git
# sudo apt-get install python-pip
# sudo pip install ansible
# echo "127.0.0.1" > ~/ansible_hosts
# export ANSIBLE_HOSTS=$HOME/ansible_hosts
# ssh-keygen
# mkdir -p /root/.ssh
# cp ~/.ssh/id_rsa.pub /root/.ssh/authorized_keys
# git clone http://github.com/skamithi/restore_pc
# cd restore_pc
# ansible-playbook site.yml

```
