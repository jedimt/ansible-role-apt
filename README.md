Ansible Role: APT Disable Background Tasks
=========

Disable automated APT background tasks on Ubuntu hosts.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

        # ===========================================================================
        # Disable APT automatic updates/upgrades
        # ===========================================================================
        - name: Disable APT updates and upgrades
        hosts: servers
        gather_facts: false

        roles:
            - ansible-role-apt-disable-background-tasks

License
-------

MIT
