---
id: common.sublist3r
title: Sublist3r
desc: ''
updated: 1642441815073
created: 1642441815073
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

