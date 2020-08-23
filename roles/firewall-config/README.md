Role Name
=========

Using this role to add/remove port or service to firewall configuration

Requirements
------------

No any requirements

Role Variables
--------------

Define variable:
add_port:       list of ports to add
add_service:    list of service to add
remove_port:    list of ports to remove
remove_service: list of service to remove

Dependencies
------------

No any dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
           add_port:
                   - 80
      roles:
         - firewall-config

License
-------

BSD

Author Information
------------------

Created by Rustam Rakhimbayev for administrating Linux hosts use
