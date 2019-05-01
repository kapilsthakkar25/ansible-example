# ansible-example

yum install ansible

git clone https://github.com/kapilsthakkar25/ansible-example

cd  ansible-example/devopslab

ansible-playbook -l webapp -i inventories/hosts.ini ping.yml

ansible-playbook -l devopslab -i inventories/hosts.ini ping.yml

ansible-playbook -l webapp -i inventories/hosts.ini httpd-install.yml

ansible-playbook -l webapp -i inventories/hosts.ini httpd-remove.yml



Refer links:

https://docs.ansible.com/ansible/latest/
