---
id: osx.whereis
title: Whereis
desc: ''
updated: 1623965016175
created: 1623965016175
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# whereis

> Locate the binary, source, and manual page files for a command.

- Locate binary, source and man pages for ssh:

`whereis {{ssh}}`

- Locate binary and man pages for ls:

`whereis -bm {{ls}}`

- Locate source of gcc and man pages for Git:

`whereis -s {{gcc}} -m {{git}}`

- Locate binaries for gcc in `/usr/bin/` only:

`whereis -b -B {{/usr/bin/}} -f {{gcc}}`

