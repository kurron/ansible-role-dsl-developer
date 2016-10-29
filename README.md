Role Name
=========

Installation of tools than any self-respecting developer of domain-specific languages loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* dsl_mps_install: true
* dsl_mps_version: 3.4
* dsl_mps_build: 34
* dsl_optional_install: false

Dependencies
------------

* kurron.jdk

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.dsl-developer, dsl_optional_install: true }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
