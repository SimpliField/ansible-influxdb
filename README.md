InfluxDb
=========

Setup InfluxDb

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
nodejs_packages_update_cache: no
```

Dependencies
------------

There is no dependency

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - { role: SimpliField.influxdb }
```

License
-------

BSD
