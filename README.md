# Ansible

install package file is dedicated to installing one or more packages on one or a couple linux servers (in my case all servers are RHEL).
I`m using an inventory file inventory.ini , where placed a list of 2 servers and variable rhel_server.
You can see the above variable in the playbook.

To run this playbook use: ansible-playbook -i inventory.ini install_package.yml

