# NGinx reverse proxy with SSL offloading and SNI support using Letsencrypt


# What you need:
* Debian Jessie host
* Ansible
* "Internet"
* Brain

# how to do it
* Add your VHosts and Upstreams into the groupvars
* Change the inventory to match your hosts IP address
* ansible-playbook -K -i inventory nginx-offloading-letsencrypt.yml
