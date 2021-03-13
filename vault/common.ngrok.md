---
id: common.ngrok
title: Ngrok
desc: ''
updated: 1615663978726
created: 1615663978726
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ngrok

> Reverse proxy that creates a secure tunnel from a public endpoint to a locally running web service.
> More information: <https://ngrok.com>.

- Expose a local HTTP service on a given port:

`ngrok http {{80}}`

- Expose a local HTTP service on a specific host:

`ngrok http {{foo.dev}}:{{80}}`

- Expose a local HTTPS server:

`ngrok http https://localhost`

- Expose TCP traffic on a given port:

`ngrok tcp {{22}}`

- Expose TLS traffic for a specific host and port:

`ngrok tls -hostname={{foo.com}} {{443}}`
