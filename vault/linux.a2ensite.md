---
id: linux.a2ensite
title: A2ensite
desc: ''
updated: 1615655543094
created: 1615655543094
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# a2ensite

> Enable an Apache virtual host on Debian-based OSes.
> More information: <https://manpages.debian.org/buster/apache2/a2ensite.8.en.html>.

- Enable a virtual host:

`sudo a2ensite {{virtual_host}}`

- Don't show informative messages:

`sudo a2ensite --quiet {{virtual_host}}`

