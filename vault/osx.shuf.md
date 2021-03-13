---
id: osx.shuf
title: Shuf
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# shuf

> Generate random permutations.

- Randomize the order of lines in a file and output the result:

`shuf {{filename}}`

- Only output the first 5 entries of the result:

`shuf -n {{5}} {{filename}}`

- Write output to another file:

`shuf {{filename}} -o {{output_filename}}`

- Generate random numbers in range 1-10:

`shuf -i {{1-10}}`

