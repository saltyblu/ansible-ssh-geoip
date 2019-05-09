ssh-geoip
=========

Enables geoip restricions from ssh

Role Variables
--------------

* allowed_countries
  * set up the allowed countires codes space seperated as string upper case
  * example
    * "DE US"

Example Playbook
----------------

```
- hosts: servers
  roles:
    - { role: ssh-geoip }
```

License
-------

MIT
