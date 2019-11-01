Ansible Role: Docker
=========

I don't remember anymore how this role got created, either its community made and modified for my own purpose or I wrote
it myself by scratch. I used it for the Docker installation on my Raspberry PI 3 running Raspbian(buster). I also tested
the role against Ubuntu 18.04(Bionic), Debian 9, Debian Buster and CentOS 7.

Requirements
------------

none

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

    - hosts: all
      roles:
         - role: xmordax.docker

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2019 by [Aljaz Gantar](https://github.com/xMordax).
