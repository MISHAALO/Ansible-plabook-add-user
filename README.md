cp -r inventories/* /etc/ansible/

cp -r roles/* /etc/ansible/roles 

ansible-playbook site.yml -e "HOST=**" -e "ROLE=users" -e "users=user