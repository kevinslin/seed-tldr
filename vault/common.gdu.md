---
id: common.gdu
title: Gdu
desc: ''
updated: 1642441815019
created: 1642441815019
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdu

> Disk usage analyzer with console interface.
> More information: <https://github.com/dundee/gdu>.

- Interactively show the disk usage of the current directory:

`gdu`

- Interactively show the disk usage of a given directory:

`gdu {{path/to/directory}}`

- Interactively show the disk usage of all mounted disks:

`gdu --show-disks`

- Interactively show the disk usage of the current directory but ignore some sub-directories:

`gdu --ignore-dirs {{path/to/directory1,path/to/directory2,...}}`

- Ignore paths by regular expression:

`gdu --ignore-dirs-pattern '{{.*[abc]+}}'`

- Ignore hidden directories:

`gdu --no-hidden`

- Only print the result, do not enter interactive mode:

`gdu --non-interactive {{path/to/directory}}`

- Do not show the progress in non-interactive mode (useful in scripts):

`gdu --no-progress {{path/to/directory}}`

