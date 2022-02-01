---
id: linux.dirb
title: Dirb
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dirb

> Scan HTTP-based webservers for directories and files.
> More information: <http://dirb.sourceforge.net>.

- Scan a webserver using the default wordlist:

`dirb {{https://example.org}}`

- Scan a webserver using a custom wordlist:

`dirb {{https://example.org}} {{path/to/wordlist.txt}}`

- Scan a webserver non-recursively:

`dirb {{https://example.org}} -r`

- Scan a webserver using a specified user-agent and cookie for HTTP-requests:

`dirb {{https://example.org}} -a {{user_agent_string}} -c {{cookie_string}}`

