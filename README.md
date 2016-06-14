QEMU
=========

A brief description of the role goes here.

Requirements
------------

Requires Anisble 1.9+

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Install QEMU 2.5.1.1 from source

    - hosts: servers
      roles:
         - { role: sergeyhush.qemu, build_from_source: yes, version: v2.5.1.1 }

License
-------

BSD

Author Information
------------------

Sergey Sudakovich
