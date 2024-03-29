---
id: common.dirsearch
title: Dirsearch
desc: ''
updated: 1642441815008
created: 1642441815008
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dirsearch

> Web path scanner.
> More information: <https://github.com/maurosoria/dirsearch>.

- Scan a web server for common paths with common extensions:

`dirsearch --url {{url}} --extensions-list`

- Scan a list of web servers for common paths with the `.php` extension:

`dirsearch --url-list {{path/to/url-list.txt}} --extensions {{php}}`

- Scan a web server for user-defined paths with common extensions:

`dirsearch --url {{url}} --extensions-list --wordlist {{path/to/url-paths.txt}}`

- Scan a web server using a cookie:

`dirsearch --url {{url}} --extensions {{php}} --cookie {{cookie}}`

- Scan a web server using the `HEAD` HTTP method:

`dirsearch --url {{url}} --extensions {{php}} --http-method {{HEAD}}`

- Scan a web server, saving the results to a `.json` file:

`dirsearch --url {{url}} --extensions {{php}} --json-report {{path/to/report.json}}`

