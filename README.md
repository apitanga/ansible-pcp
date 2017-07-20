PCP
===

Installs, enables and starts pmloger and pmcd.

Requirements
------------

Requires a RHEL7.2 host, and each host must have the pcp RPM package available to it via some yum repo (i.e. rhel-7-server-rpms).

Role Variables
--------------

None yet.

Dependencies
------------

I'm not aware of any. Only works for RHEL 7.2 for now though.


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
