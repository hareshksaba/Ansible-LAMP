# Ansible-HAProxy-LAMP-Stack
This article will help create a LAMP stack using ansible playbook with roles.

This playbook will create a LAMP stack with a HAProxy LoadBalancer.

To Run the Playbook,

1. Update hosts file with your test machine ip address
2. make sure you have sudo access
3. Update group_vars for lbservers with the same ipaddress
3. run the following command from this folder. 
    ansible-playbook -i hosts -s -u user_name site.yml --ask-sudo-pass

