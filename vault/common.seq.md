---
id: common.seq
title: Seq
desc: ''
updated: 1623965016149
created: 1623965016149
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# seq

> Output a sequence of numbers to stdout.
> More information: <https://www.gnu.org/software/coreutils/seq>.

- Sequence from 1 to 10:

`seq 10`

- Every 3rd number from 5 to 20:

`seq 5 3 20`

- Separate the output with a space instead of a newline:

`seq -s " " 5 3 20`

- Format output width to a minimum of 4 digits padding with zeros as necessary:

`seq -f "%04g" 5 3 20`

