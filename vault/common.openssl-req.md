---
id: common.openssl-req
title: Openssl Req
desc: ''
updated: 1623965016141
created: 1623965016141
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openssl req

> OpenSSL command to manage PKCS#10 Certificate Signing Requests.
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-req.html>.

- Generate a certificate signing request to be sent to a certificate authority:

`openssl req -new -sha256 -key {{filename.key}} -out {{filename.csr}}`

- Generate a self-signed certificate and a corresponding key-pair, storing both in a file:

`openssl req -new -x509 -newkey {{rsa}}:{{4096}} -keyout {{filename.key}} -out {{filename.cert}} -subj "{{/C=XX/CN=foobar}}" -days {{365}}`

