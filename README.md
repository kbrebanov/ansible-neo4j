neo4j
=====

Installs Neo4j

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

None

Dependencies
------------

- kbrebanov.java (OpenJDK 8)

Example Playbook
----------------

Install Neo4j
```
- hosts: all
  roles:
    - kbrebanov.neo4j
```

Install older version of Neo4j
```
- hosts: all
  vars:
    neo4j_version: 2.2.0
  roles:
    - kbrebanov.neo4j
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
