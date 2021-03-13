---
id: linux.mcookie
title: Mcookie
desc: ''
updated: 1615655543105
created: 1615655543105
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mcookie

> Generates random 128 bit hexadecimal numbers.

- Generate a random number:

`mcookie`

- Generate a random number, using the contents of a file as a seed for the randomness:

`mcookie --file {{path/to/file}}`

- Generate a random number, using a specific number of bytes from a file as a seed for the randomness:

`mcookie --file {{path/to/file}} --max-size {{number_of_bytes}}`

- Print the details of the randomness used, such as the origin and seed for each source:

`mcookie --verbose`

