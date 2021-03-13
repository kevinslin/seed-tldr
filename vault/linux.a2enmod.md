---
id: linux.a2enmod
title: A2enmod
desc: ''
updated: 1615655543094
created: 1615655543094
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# a2enmod

> Enable an Apache module on Debian-based OSes.
> More information: <https://manpages.debian.org/buster/apache2/a2enmod.8.en.html>.

- Enable a module:

`sudo a2enmod {{module}}`

- Don't show informative messages:

`sudo a2enmod --quiet {{module}}`

