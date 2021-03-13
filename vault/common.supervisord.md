---
id: common.supervisord
title: Supervisord
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# supervisord

> Supervisor is a client/server system for controlling some processes on UNIX-like operating systems.
> Supervisord is the server part of supervisor; it is primarily managed via a configuration file.
> More information: <http://supervisord.org>.

- Start supervisord with specified configuration file:

`supervisord -c {{path/to/file}}`

- Run supervisord in the foreground:

`supervisord -n`

