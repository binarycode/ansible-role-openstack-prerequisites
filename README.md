Ansible Role: OpenStack prerequisites
=========

This role installs prerequisites (such as the openstack repo and a few packages) for OpenStack installation on EL-based system.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: binarycode.openstack-prerequisites

License
-------

BSD

Author Information
------------------

[Igor Sidorov](https://github.com/binarycode)
