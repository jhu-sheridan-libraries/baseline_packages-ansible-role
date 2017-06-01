Baseline_Packages Ansible Role 
=========

Just a role that installs a bunch of packages, nothing special.

Requirements
------------

N/A

Role Variables
--------------

packages: []

This variable is a list of packages that will be installed by the role.

Dependencies
------------

Tested on Ansible 2.3

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: baseline_packages, packages: ['vim', 'sysstat', 'fail2ban'] }

License
-------

TBD

Author Information
------------------

Derek Belrose <dbelrose@jhu.edu>