Security Zones Configuration
=========

Configure Security Zones for Junos.

Requirements
------------


Role Variables
--------------
security_zones: List of Dictionaries containing Security Zones

security_zones_settings: Dictionary containing settings for Security Zones


Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_security_zones_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
