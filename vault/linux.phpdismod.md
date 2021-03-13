---
id: linux.phpdismod
title: Phpdismod
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# phpdismod

> Disable PHP extensions on Debian-based OSes.

- Disable the json extension for every SAPI of every PHP version:

`sudo phpdismod {{json}}`

- Disable the json extension for PHP 7.3 with the cli SAPI:

`sudo phpdismod -v {{7.3}} -s {{cli}} {{json}}`

