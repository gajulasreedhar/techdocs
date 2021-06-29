# Kubernetes Installation
# To Create a User in Ubuntu follow the below steps:
$ adduser username

#Add the new user to the sudo group 
usermod -aG sudo username

Switch to newly created user:
su - username

#How to Enable SSH Password Authentication
#To enable SSH password authentication, you must SSH in as root to edit this file:
/etc/ssh/sshd_config

PasswordAuthentication yes

sudo service ssh restart

