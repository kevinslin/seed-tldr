---
id: common.mkcert
title: Mkcert
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

