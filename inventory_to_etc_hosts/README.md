# Ansible
My ansible projects

This a playbook I made so I can easily configure the /etc/hosts of managed nodes with the same hostname they use in ansible inventory file.
The only required variable is ansible_host (and I suggest to be placed in host_vars folder for each node) and adding the group name to the loop.


This only works of ansible-host is an IP address.

later I will add fqdn support
