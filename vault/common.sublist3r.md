---
id: common.sublist3r
title: Sublist3r
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# sublist3r

> Fast subdomains enumeration tool for penetration testers.
> More information: <https://github.com/aboul3la/Sublist3r>.

- Find subdomains for a domain:

`sublist3r --domain {{domain_name}}`

- Find subdomains for a domain, also enabling brute force search:

`sublist3r --domain {{domain_name}} --bruteforce`

- Save the found subdomains to a text file:

`sublist3r --domain {{domain_name}} --output {{path/to/output_file}}`

- Output all available options:

`sublist3r --help`

