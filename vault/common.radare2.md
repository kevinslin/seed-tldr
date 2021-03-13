---
id: common.radare2
title: Radare2
desc: ''
updated: 1615663978731
created: 1615663978731
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# radare2

> A set of reverse engineering tools.
> More information: <https://radare.gitbooks.io/radare2book/>.

- Open a file in write mode without parsing the file format headers:

`radare2 -nw {{path/to/binary}}`

- Debug a program:

`radare2 -d {{path/to/binary}}`

- Run a script before entering the interactive CLI:

`radare2 -i {{path/to/script.r2}} {{path/to/binary}}`

- Show help text for any command in the interactive CLI:

`> {{radare2_command}}?`

- Run a shell command from the interactive CLI:

`> !{{shell_command}}`

- Dump raw bytes of current block to a file:

`> pr > {{path/to/file.bin}}`

