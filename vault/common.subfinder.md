---
id: common.subfinder
title: Subfinder
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# subfinder

> A subdomain discovery tool that discovers valid subdomains for websites.
> Designed as a passive framework to be useful for bug bounties and safe for penetration testing.
> More information: <https://github.com/subfinder/subfinder>.

- Find subdomains for a specific domain:

`subfinder -d {{example.com}}`

- Show only the subdomains found:

`subfinder --silent -d {{example.com}}`

- Use bruteforcing to find subdomains:

`subfinder -d {{example.com}} -b`

- Remove wildcard subdomains:

`subfinder -nW -d {{example.com}}`

- Use a given comma-separated list of resolvers:

`subfinder -r {{8.8.8.8}},{{1.1.1.1}} -d {{example.com}}`

