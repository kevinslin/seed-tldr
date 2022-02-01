---
id: common.calibre-server
title: Calibre Server
desc: ''
updated: 1642441815000
created: 1642441815000
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# calibre-server

> A server application that can be used to distribute e-books over a network.
> Note: e-books must already be imported into the library using the GUI or the `calibredb` CLI.
> More information: <https://manual.calibre-ebook.com/generated/en/calibre-server.html>.

- Start a server to distribute e-books. Access at http&#x3A;//localhost:8080:

`calibre-server`

- Start server on different port. Access at http&#x3A;//localhost:port:

`calibre-server --port {{port}}`

- Password protect the server:

`calibre-server --username {{username}} --password {{password}}`

