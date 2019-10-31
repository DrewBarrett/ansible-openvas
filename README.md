Role Name
=========

Installs openvas as a Docker container using either the `docker` daemon or `docker-systemd-service'

Requirements
------------
Docker and docker python module

Role Variables
--------------
See `defaults/main.yml`

Dependencies
------------

If you want to use the systemd service provider, `drewbarrett.docker-systemd-service`

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: drewbarrett.openvas, provider: systemd }

License
-------

MIT
