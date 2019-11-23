fix_empty_etc_resolv_conf
=========
Fix the empty resolv.conf that a broken cloud-init leaves behind...


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
         - { role: johanneskastl.fix_empty_etc_resolv_conf}

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
