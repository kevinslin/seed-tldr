---
id: linux.nm
title: Nm
desc: ''
updated: 1615655543106
created: 1615655543106
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nm

> List symbol names in object files.

- List global (extern) functions in a file (prefixed with T):

`nm -g {{file.o}}`

- List only undefined symbols in a file:

`nm -u {{file.o}}`

- List all symbols, even debugging symbols:

`nm -a {{file.o}}`

- Demangle C++ symbols (make them readable):

`nm --demangle {{file.o}}`

