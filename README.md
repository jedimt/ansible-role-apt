Ansible Role: APT
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
          - jedimt.apt

License
-------

MIT

Author Information
------------------

Aaron Patten
aaronpatten@gmail.com
