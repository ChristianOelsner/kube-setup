# kube-setup
Simple playbook to setup at kubernetes cluster at home. Targeted at CentOS 7
Needs a lot more tweaking, but it gets the job done.

Simply edit the hosts file and run:
ansible-playbook -i hosts setup.yml --ask-become
