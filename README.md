Ansible Role: Supervisor
========================

Install Supervisor on CentOS 7 servers. this role suit for china, pip source is http://pypi.douban.com/simple.

Requirements
------------

Written in Ansible 2.0.*

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

### config_dir

Directory where supervisord reads configuration files.

Default is `/etc/supervisor.d`.

Dependencies
------------

- python2.7

Example Playbook
----------------

    - hosts: servers
      roles:
        - liubin.supervisor

License
-------

MIT

Author Information
------------------

This role was created in 2016 by [Juwai Limited](http://www.juwai.com).