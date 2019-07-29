# pm2

[![Build Status](https://travis-ci.com/treinberger/ansible-role-pm2.svg?branch=master)](https://travis-ci.com/treinberger/ansible-role-pm2)

Ansible role for pm2

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install treinberger.pm2`

# Default settings

```

pm2_user: www-data
pm2_startup: systemv
pm2_home: /var/www/.pm2
pm2_version: 2.4.4

```
