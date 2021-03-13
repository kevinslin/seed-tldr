---
id: common.live-server
title: Live Server
desc: ''
updated: 1615655543067
created: 1615655543067
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

