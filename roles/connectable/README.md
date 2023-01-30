Connectable
=========

This role is used to test host connectivity. Not for production use.

Requirements
------------

Ansible 2.4 or higher

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

This is an example playbook that uses the role:

    - hosts: all
      become: true
      gather_facts: false
      roles:
        - connectable

License
-------

MIT

Author Information
------------------

Anthony Pagan
