# mailad-ansible
Ansible implementation of [MailAD](https://github.com/stdevPavelmc/mailad)

How to use:

`ansible-playbook playbooks/mailad-server-setup.yml -i inventories/hosts.yml -l mail.mailad.cu`

It requires a running Ubuntu 20.04 (focal) server and an Ansible controller.

This is a draft revision, some configs were not tested. Use at your own risk!
