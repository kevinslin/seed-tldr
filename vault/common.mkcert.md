---
id: common.mkcert
title: Mkcert
desc: ''
updated: 1642441815047
created: 1642441815047
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkcert

> Tool for making locally-trusted development certificates.
> More information: <https://github.com/FiloSottile/mkcert>.

- Install the local CA in the system trust store:

`mkcert -install`

- Generate certificate and private key for a given domain:

`mkcert {{example.org}}`

- Generate certificate and private key for multiple domains:

`mkcert {{example.org}} {{myapp.dev}} {{127.0.0.1}}`

- Generate wildcard certificate and private key for a given domain and its subdomains:

`mkcert "{{*.example.it}}"`

- Uninstall the local CA:

`mkcert -uninstall`

