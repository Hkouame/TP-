Role Name
=========

Install openjdk

Requirements
------------

None.

Role Variables
--------------

Default variables are defined in defaults/ and vars/ directory :

| Variable | Default value | Description |
| -------- | ------------- | ----------- |
| `openjdk_version` | 8 | OpenJDK version to install |


Dependencies
------------

None.

Example Playbook
----------------

OpenJDK :
```YAML
    - hosts: all
      roles:
         - role: openjdk
           openjdk_version: 8
```
