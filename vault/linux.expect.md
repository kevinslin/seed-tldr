---
id: linux.expect
title: Expect
desc: ''
updated: 1642441815094
created: 1642441815094
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# expect

> Script executor that interacts with other programs that require user input.
> More information: <https://manned.org/expect>.

- Execute an expect script from a file:

`expect {{path/to/file}}`

- Execute a specified expect script:

`expect -c "{{commands}}"`

- Enter an interactive REPL (use `exit` or Ctrl + D to exit):

`expect -i`

