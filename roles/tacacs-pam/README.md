Role Name
=========

Ansible role which will configure tacacs support on an ubuntu system

Role Variables
--------------

vars/main.yml

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


Example Playbook
----------------

Example of running:

ansible-playbook configure-tacacs-pam.yml --limit cloudlab  --ask-vault-pass -e tacacs_secret=123456

License
-------

BSD

Author Information
------------------
github.com/pertoftAn optional section for the role authors to include contact information, or a website (HTML is not allowed).
