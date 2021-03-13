---
id: linux.fc-list
title: Fc List
desc: ''
updated: 1615655543100
created: 1615655543100
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# fc-list

> List available fonts installed on the system.

- Return a list of installed fonts in your system:

`fc-list`

- Return a list of installed fonts with given name:

`fc-list | grep '{{DejaVu Serif}}'`

- Return the number of installed fonts in your system:

`fc-list | wc -l`

