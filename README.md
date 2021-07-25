# mailad-ansible
Ansible implementation of [MailAD](https://github.com/stdevPavelmc/mailad)

How to use:

1. Prepare your Ansible controller and your prospect Ubuntu 20.04 (focal) mail server.
2. Generate certificates (self-signed or authentic) for your prospect mail server.
3. Run the playbook: `ansible-playbook playbooks/mailad-server-setup.yml -i inventories/hosts.yml -l mail.mailad.cu`
4. Mail server should now be ready.

This is a draft revision, some configs were not tested. Use at your own risk!
