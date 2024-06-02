# ansible-netbox-docker

Ansible-playbook for install netbox-docker on remote hosts with Debian12 OS.  
Use netbox-docker project - https://github.com/netbox-community/netbox-docker.

`ansible-playbook host-install_netbox-docker.yaml -u <username> --ask-pass -K`

You can change netbox superuser login and password in playbook section **vars:**
