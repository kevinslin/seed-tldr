---
id: common.fd
title: Fd
desc: ''
updated: 1615655543054
created: 1615655543054
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# fd

> An alternative to `find`.
> Aims to be faster and easier to use than `find`.
> More information: <https://github.com/sharkdp/fd>.

- Recursively find files matching the given pattern in the current directory:

`fd {{pattern}}`

- Find files that begin with "foo":

`fd {{'^foo'}}`

- Find files with a specific extension:

`fd --extension {{txt}}`

- Find files in a specific directory:

`fd {{pattern}} {{path/to/directory}}`

- Include ignored and hidden files in the search:

`fd --hidden --no-ignore {{pattern}}`

- Execute a command on each search result returned:

`fd {{pattern}} --exec {{command}}`

