Ansible Role - PhantomJS
========================

A phantomjs role to install phantomjs on elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Role Variables
--------------

* version: (optionnal) PhantomJS version

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.phantomjs }

License
-------

MIT

Author Information
------------------

http://www.elao.com/
