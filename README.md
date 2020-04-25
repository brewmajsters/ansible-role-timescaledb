# timescaledb

[![Build Status](https://travis-ci.org/brewmajsters/ansible-role-timescaledb.svg?branch=master)](https://travis-ci.org/brewmajsters/ansible-role-timescaledb)

Download and install postgresql database and add the TimeScaleDB extension.

## Requirements

None

## Role Variables

    timescaledb_database_user: <str, postgresql username>
    timescaledb_database_password: <str, postgresql user password>
    timescaledb_database_name: <str, postgresql database to be created>

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
