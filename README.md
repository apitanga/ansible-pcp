PCP
===

Installs, enables and starts pmloger and pmcd.

Requirements
------------

Host must have the pcp RPM packages available to it via some yum repo (i.e. rhel-7-server-rpms).

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: apitanga.pcp }

License
-------

GPL


Author Information
------------------

Andre Pitanga <apitanga@redhat.com>
