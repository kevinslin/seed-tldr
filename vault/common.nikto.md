---
id: common.nikto
title: Nikto
desc: ''
updated: 1615655543074
created: 1615655543074
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nikto

> Web server scanner which performs tests against web servers for multiple items.
> More information: <https://cirt.net/Nikto2>.

- Perform a basic Nikto scan against a target host:

`perl nikto.pl -h {{192.168.0.1}}`

- Specify the port number when performing a basic scan:

`perl nikto.pl -h {{192.168.0.1}} -p {{443}}`

- Scan ports and protocols with full URL syntax:

`perl nikto.pl -h {{https://192.168.0.1:443/}}`

- Scan multiple ports in the same scanning session:

`perl nikto.pl -h {{192.168.0.1}} -p {{80,88,443}}`

- Update to the latest plugins and databases:

`perl nikto.pl -update`

