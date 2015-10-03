Role Name
=========

This role is to make a simple router functionality.

I have decided to draw the line at CARP and other redundancy services.

The use-case that I am aiming at is to do "vagrant up" and start a small sub-network with a router and some server. This is mainly used for testing environments - for actual security, some tweaking is necessary.

Requirements
------------

none

Role Variables
--------------

Look in vars/main.yml, or the examples in the tests directory.

Dependencies
------------

none

Example Playbook
----------------

Look in the tests directory for an example vagrant configuration. 

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: test_router
      roles:
         - { role: router-single, x: 42 }

License
-------

BSD

Author Information
------------------

This project is found on github.

http://github.com/moozer


Any issues, pull requests and such should go into the issues system on github.


