PCP
===

Installs, enables and starts pmlogger and pmcd.

Requirements
------------

Host must have the `pcp` RPM packages available to it via some yum repo (i.e. `rhel-7-server-rpms`).

Role Variables
--------------

(Optional) `pcp_logging_interval` changes logging (sampling) interval from default 60 seconds to value set here, in seconds.
(Optional) `pcp_remote_hosts` restricts remote access to pmcd service to specific hosts listed here. A wildcarded IP or IPv6 address may be used to specify groups of hosts, as per https://pcp.io/books/PCP_UAG/html/id5191707.html.

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
