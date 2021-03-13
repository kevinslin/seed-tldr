---
id: common.openssl-prime
title: Openssl Prime
desc: ''
updated: 1615655543076
created: 1615655543076
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# openssl prime

> OpenSSL command to compute prime numbers.
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-prime.html>.

- Generate a 2048bit prime number and display it in hexadecimal:

`openssl prime -generate -bits 2048 -hex`

- Check if a given number is prime:

`openssl prime {{number}}`

