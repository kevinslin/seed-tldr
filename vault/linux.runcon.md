---
id: linux.runcon
title: Runcon
desc: ''
updated: 1615655543108
created: 1615655543108
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# runcon

> Run a program in a different SELinux security context.
> With neither context nor command, print the current security context.

- Determine the current domain:

`runcon`

- Specify the domain to run a command in:

`runcon -t {{domain}}_t {{command}}`

- Specify the context role to run a command with:

`runcon -r {{role}}_r {{command}}`

- Specify the full context to run a command with:

`runcon {{user}}_u:{{role}}_r:{{domain}}_t {{command}}`

