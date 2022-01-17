---
id: linux.ncdu
title: Ncdu
desc: ''
updated: 1642441815105
created: 1642441815105
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ncdu

> Disk usage analyzer with an ncurses interface.
> More information: <https://manned.org/ncdu>.

- Analyze the current working directory:

`ncdu`

- Colorize output:

`ncdu --color {{dark|off}}`

- Analyze a given directory:

`ncdu {{path/to/directory}}`

- Save results to a file:

`ncdu -o {{path/to/file}}`

- Exclude files that match a pattern, argument can be given multiple times to add more patterns:

`ncdu --exclude '{{*.txt}}'`

