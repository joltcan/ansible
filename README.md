# ansible
misc ansible stuff

This is my first public ansible repo, so stuff might not work etc, but I've used them, so they might. Just make sure to edit the hosts-file per your setup.

## update.yml
This file is what I use most. Since running apt-get update / upgrade is boring I use this:

ansible-playbook update.yml --extra-vars "target=somehostlimit" (or all) (see http://stackoverflow.com/questions/18195142/safely-limiting-ansible-playbooks-to-a-single-machine)

