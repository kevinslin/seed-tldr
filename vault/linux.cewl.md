---
id: linux.cewl
title: Cewl
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cewl

> URL spidering tool for making a cracking wordlist from web content.
> More information: <https://digi.ninja/projects/cewl.php>.

- Create a wordlist file from the given URL up to 2 links depth:

`cewl --depth {{2}} --write {{path/to/wordlist.txt}} {{url}}`

- Output an alphanumeric wordlist from the given URL with words of minimum 5 characters:

`cewl --with-numbers --min_word_length {{5}} {{url}}`

- Output a wordlist from the given URL in debug mode including email addresses:

`cewl --debug --email {{url}}`

- Output a wordlist from the given URL using HTTP Basic or Digest authentication:

`cewl --auth_type {{basic|digest}} --auth_user {{username}} --auth_pass {{password}} {{url}}`

- Output a wordlist from the given URL through a proxy:

`cewl --proxy_host {{host}} --proxy_port {{port}} {{url}}`

