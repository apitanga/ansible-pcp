PCP
===

Installs, enables and starts pmlogger and pmcd.

Requirements
------------

Host must have the `pcp` RPM packages available to it via some yum repo (i.e. `rhel-7-server-rpms`).

Role Variables
--------------

(Optional) `pcp_logging_interval` changes logging (sampling) interval from default 60 seconds to value set here, in seconds.

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
