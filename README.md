marklee77.tor
============

[![Build Status](https://travis-ci.org/marklee77/ansible-role-tor.svg?branch=master)](https://travis-ci.org/marklee77/ansible-role-tor)

Role to install tor on Ubuntu.

This role is currently under development and is only partially functional.

Example Playbook
-------------------------

    - hosts: all
      roles:
        - marklee77.tor

License
-------

GPLv2

Author Information
------------------

http://stillwell.me

Todo
----
- figure out solution to squid/upstart to get it working nicely in 
  vagrant/docker
- dnsmasq to cache queries and pass up to docker...resolveconf?
