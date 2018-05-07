
#  Update Ec2 variables in /ec2-vars/testserver.yml and then run playbook.

>> ansible-playbook -vvvv -i hosts, -e "type=testserver" provision-ec2.yml



