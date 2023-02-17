lighthouse
=========

This role installs lighthouse

Requirements
------------

Pre-installed nginx

Role Variables
--------------

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| domain | mydomain.org | nginx site name |
| nginx_user | nginx | nginx user |

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lighthouse }

License
-------

MIT

Author Information
------------------

Petr Losev  
wowpetr@gmail.com