---
id: common.openssl-prime
title: Openssl Prime
desc: ''
updated: 1615663978728
created: 1615663978728
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openssl prime

> OpenSSL command to compute prime numbers.
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-prime.html>.

- Generate a 2048bit prime number and display it in hexadecimal:

`openssl prime -generate -bits 2048 -hex`

- Check if a given number is prime:

`openssl prime {{number}}`

