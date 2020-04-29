Role Name
=========

Ansible role to provision mitmproxy on debian based distributions. It also adds the necessary firewall rules to make the target act both as a normal proxy and proxy gateway (mitmproxy normal and gateway mode)

Requirements
------------

None.

Role Variables
--------------

Use the following variable to override mitmproxy version 
- mitmproxy_ver

Role adds binaries to /usr/bin/local by default, use the following to override behaviour
- bin_path

Dependencies
------------

None.

Example Playbook
----------------

TODO

License
-------

GPL

Author Information
------------------

TODO
