---
id: linux.w
title: W
desc: ''
updated: 1642441815117
created: 1642441815117
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# w

> Display who is logged in and their processes.
> More information: <https://www.geeksforgeeks.org/w-command-in-linux-with-examples/>.

- Display information about all users who are currently logged in:

`w`

- Display information about a specific user:

`w {{user}}`

- Display information without including the header:

`w --no-header`

- Display information without including the login, JCPU and PCPU columns:

`w --short`

