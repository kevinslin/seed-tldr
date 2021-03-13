---
id: common.gdb
title: Gdb
desc: ''
updated: 1615663978711
created: 1615663978711
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdb

> The GNU Debugger.
> More information: <https://www.gnu.org/software/gdb>.

- Debug an executable:

`gdb {{executable}}`

- Attach a process to gdb:

`gdb -p {{procID}}`

- Debug with a core file:

`gdb -c {{core}} {{executable}}`

- Execute given GDB commands upon start:

`gdb -ex "{{commands}}" {{executable}}`

- Start gdb and pass arguments to the executable:

`gdb --args {{executable}} {{argument1}} {{argument2}}`

