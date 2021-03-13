---
id: linux.a2dismod
title: A2dismod
desc: ''
updated: 1615655543094
created: 1615655543094
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# a2dismod

> Disable an Apache module on Debian-based OSes.
> More information: <https://manpages.debian.org/buster/apache2/a2dismod.8.en.html>.

- Disable a module:

`sudo a2dismod {{module}}`

- Don't show informative messages:

`sudo a2dismod --quiet {{module}}`

