---
id: common.psgrep
title: Psgrep
desc: ''
updated: 1642441815061
created: 1642441815061
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# psgrep

> Search running processes with `grep`.
> More information: <https://jvz.github.io/psgrep>.

- Find process lines containing a specific string:

`psgrep {{process_name}}`

- Find process lines containing a specific string, excluding headers:

`psgrep -n {{process_name}}`

- Search using a simplified format (PID, user, command):

`psgrep -s {{process_name}}`

