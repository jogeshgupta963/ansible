ansible-inventory --list -y -i /home/ubuntu/ansible

ansible all -m ping -i /home/ubuntu/ansible/hosts --private-key=~/.ssh/ansible_key

ansible-playbook create-user.yaml -i /home/ubuntu/ansible/hosts --private-key=~/.ssh/ansible_key
