---
id: common.htpasswd
title: Htpasswd
desc: ''
updated: 1615655543063
created: 1615655543063
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# htpasswd

> Create and manage htpasswd files to protect web server directories using basic authentication.
> More information: <https://httpd.apache.org/docs/current/programs/htpasswd.html>.

- Create/overwrite htpasswd file:

`htpasswd -c {{path/to/file}} {{username}}`

- Add user to htpasswd file or update existing user:

`htpasswd {{path/to/file}} {{username}}`

- Add user to htpasswd file in batch mode without an interactive password prompt (for script usage):

`htpasswd -b {{path/to/file}} {{username}} {{password}}`

- Delete user from htpasswd file:

`htpasswd -D {{path/to/file}} {{username}}`

- Verify user password:

`htpasswd -v {{path/to/file}} {{username}}`

- Display a string with username (plain text) and password (md5):

`htpasswd -nbm {{username}} {{password}}`

