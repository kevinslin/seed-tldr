---
id: linux.uuidgen
title: Uuidgen
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# uuidgen

> Generate unique identifiers (UUIDs).

- Create a random UUID:

`uuidgen --random`

- Create a UUID based on the current time:

`uuidgen --time`

- Create a UUID based on the hash of a URL:

`uuidgen --sha1 --namespace {{@url}} --name {{object_name}}`

