---
id: linux.addr2line
title: Addr2line
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# addr2line

> Convert addresses of a binary into file names and line numbers.

- Display the filename and line number of the source code from an instruction address of an executable:

`addr2line --exe={{path/to/executable}} {{address}}`

- Display the function name, filename and line number:

`addr2line --exe={{path/to/executable}} --functions {{address}}`

- Demangle the function name for C++ code:

`addr2line --exe={{path/to/executable}} --functions --demangle {{address}}`

