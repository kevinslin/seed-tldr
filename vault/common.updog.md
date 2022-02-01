---
id: common.updog
title: Updog
desc: ''
updated: 1642441815079
created: 1642441815079
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# updog

> A replacement for Python's SimpleHTTPServer.
> It allows uploading and downloading via HTTP/S, can set ad hoc SSL certificates and use HTTP basic auth.
> More information: <https://github.com/sc0tfree/updog>.

- Start a HTTP server for the current directory:

`updog`

- Start a HTTP server for a specified directory:

`updog --directory {{/path/to/directory}}`

- Start a HTTP server on a specified port:

`updog --port {{port}}`

- Start a HTTP server with a password (To log in, leave the username blank and enter the password in the password field):

`updog --password {{password}}`

- Enable transport encryption via SSL :

`updog --ssl`

