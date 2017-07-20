PCP
===

Installs, enables and starts pmloger and pmcd.

Requirements
------------

Requires RHEL7 and all system must have the pcp RPM package available to it via some yum repo.

Role Variables
--------------

None yet.

Dependencies
------------

I'm not aware of any. Only works for RHEL 7.2 for now.


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
