---
id: common.live-server
title: Live Server
desc: ''
updated: 1623965016135
created: 1623965016135
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# live-server

> A simple development http server with live reload capability.
> More information: <https://www.npmjs.com/package/live-server>.

- Serve an `index.html` file and reload on changes:

`live-server`

- Specify a port (default is 8080) from which to serve a file:

`live-server --port={{8081}}`

- Specify a given file to serve:

`live-server --open={{about.html}}`

- Proxy all requests for ROUTE to URL:

`live-server --proxy={{/}}:{{http:localhost:3000}}`

