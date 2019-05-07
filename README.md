# ssh-controls
ssh controls to either grant or revoke users login to set of machines

the task is being written for use by ansible

the inventory directory consists of hosts.yaml file in which the hosts can be added 

the user name can be sent dynamically via command line and the actions can also be declared via command line

below is the example syntax

ansible-playbook -i inventory/hosts.yml -e "username='sureshby' user_action=revoke" site.yml

user_action can be grant and revoke
we can go ahead adding number of hosts in the file hosts.yml
