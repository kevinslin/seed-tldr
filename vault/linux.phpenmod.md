---
id: linux.phpenmod
title: Phpenmod
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# phpenmod

> Enable PHP extensions on Debian-based OSes.

- Enable the json extension for every SAPI of every PHP version:

`sudo phpenmod {{json}}`

- Enable the json extension for PHP 7.3 with the cli SAPI:

`sudo phpenmod -v {{7.3}} -s {{cli}} {{json}}`

