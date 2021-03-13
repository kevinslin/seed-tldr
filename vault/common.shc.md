---
id: common.shc
title: Shc
desc: ''
updated: 1615655543085
created: 1615655543085
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# shc

> Generic shell script compiler.

- Compile a shell script:

`shc -f {{script}}`

- Compile a shell script and specify an output binary file:

`shc -f {{script}} -o {{binary}}`

- Compile a shell script and set an expiration date for the executable:

`shc -f {{script}} -e {{dd/mm/yyyy}}`

- Compile a shell script and set a message to display upon expiration:

`shc -f {{script}} -e {{dd/mm/yyyy}} -m "{{Please contact your provider}}"`

