---
id: common.openssl-genpkey
title: Openssl Genpkey
desc: ''
updated: 1623965306201
created: 1623965306201
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openssl genpkey

> OpenSSL command to generate asymmetric key pairs.
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-genpkey.html>.

- Generate an RSA private key of 2048 bits, saving it to a specific file:

`openssl genpkey -algorithm rsa -pkeyopt rsa_keygen_bits:{{2048}} -out {{filename.key}}`

- Generate an elliptic curve private key using the curve `prime256v1`, saving it to a specific file:

`openssl genpkey -algorithm EC -pkeyopt ec_paramgen_curve:{{prime256v1}} -out {{filename.key}}`

- Generate an `ED25519` elliptic curve private key, saving it to a specific file:

`openssl genpkey -algorithm {{ED25519}} -out {{filename.key}}`

