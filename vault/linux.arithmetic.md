---
id: linux.arithmetic
title: Arithmetic
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# arithmetic

> Quiz on simple arithmetic problems.
> More information: <https://manpages.debian.org/bsdgames/arithmetic.6.en.html>.

- Start an arithmetic quiz:

`arithmetic`

- Specify one or more arithmetic [o]peration symbols to get problems on them:

`arithmetic -o {{+|-|x|/}}`

- Specify a range. Addition and multiplication problems would feature numbers between 0 and range, inclusive. Subtraction and division problems would have required result and number to be operated on, between 0 and range:

`arithmetic -r {{7}}`

