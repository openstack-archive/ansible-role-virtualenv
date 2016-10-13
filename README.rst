=======================
ansible-role-virtualenv
=======================

Ansible role to manage Virtualenv

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-virtualenv.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-virtualenv
* Bugs: https://bugs.launchpad.net/ansible-role-virtualenv

Description
-----------

Virtualenv is a tool to create isolated Python environments.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Sudo
~~~~

You will be required to create the appropriate sudoers file if you plan on
creating DIBs.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install virtualenv
      hosts: all
      roles:
        - ansible-role-virtualenv
