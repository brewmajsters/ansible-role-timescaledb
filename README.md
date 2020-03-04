# timescaledb

[![Build Status](https://travis-ci.org/brewmajsters/ansible-role-timescaledb.svg?branch=master)](https://travis-ci.org/brewmajsters/ansible-role-timescaledb)

Download and install postgresql database and add the TimeScaleDB extension.

## Requirements

None

## Role Variables

    debian_postgresql_database_user: <str, postgresql username>
    debian_postgresql_database_password: <str, postgresql user password>
    debian_postgresql_database_name: <str, postgresql database to be created>
    timescaledb_as_docker: <bool, if true, timescaledb is deployed as docker image>

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
         - role: ansible-role-timescaledb

## License

None

## Author Information

Tomas Bellus
