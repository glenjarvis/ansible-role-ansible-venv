ansible_venv
============
A default virtual environment for when you want to keep your Ansible isolated
from the rest of your system.

Requirements
------------
None

Role Variables
--------------

* _ansible_venv_base: /opt/venvs
* _ansible_venv_owner: root
* _ansible_venv_group: root
* _ansible_venv_mode: '0755'
* _ansible_venv_seed_python_exec: /usr/bin/python3
* _ansible_venv_name: ansible-current

Dependencies
------------
None

Example Playbook
----------------

    - hosts: servers
      roles:
         - ansible_venv

License
-------
MIT

Author Information
------------------

Glen Jarvis <glen@glenjarvis.com>
