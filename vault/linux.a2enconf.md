---
id: linux.a2enconf
title: A2enconf
desc: ''
updated: 1615655543094
created: 1615655543094
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# a2enconf

> Enable an Apache configuration file on Debian-based OSes.
> More information: <https://manpages.debian.org/buster/apache2/a2enconf.8.en.html>.

- Enable a configuration file:

`sudo a2enconf {{configuration_file}}`

- Don't show informative messages:

`sudo a2enconf --quiet {{configuration_file}}`

