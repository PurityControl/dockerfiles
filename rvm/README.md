# RVM

## Purpose

This installs rvm system wide. It requires the use of the sudo package
as described in the section
[Multi-User Installs - Using the sudo command](https://rvm.io/support/troubleshooting)
as rvm should not be installed by the root user.

### Dependencies

- sudo
- libpqdev
- puritycontrol/ubuntu-dev:16.04 docker image

#### Libpqdev

Libpqdev has been installed as postgresql is a common requirement of
ruby and rails projects.

## Versions

The following versions are available:

- bare  (the rvm installation but no ruby installed yet)
