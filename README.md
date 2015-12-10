NFS Client Ansible role
=======================

Configures NFS mount points.

Role Variables
--------------

    nfs_client_mountpoints:
      - dev:
        dir:

Example Playbook
----------------

    - hosts: localhost
      roles:
         - role: nfs_client
           nfs_client_mountpoints:
             - dev: someserver:/this/path
               dir: /mnt/point

License
-------

MIT
