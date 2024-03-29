---
id: linux.as
title: As
desc: ''
updated: 1642441815088
created: 1642441815088
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# as

> Portable GNU assembler.
> Primarily intended to assemble output from `gcc` to be used by `ld`.
> More information: <https://manned.org/as>.

- Assemble a file, writing the output to `a.out`:

`as {{file.s}}`

- Assemble the output to a given file:

`as {{file.s}} -o {{out.o}}`

- Generate output faster by skipping whitespace and comment preprocessing. (Should only be used for trusted compilers):

`as -f {{file.s}}`

- Include a given path to the list of directories to search for files specified in `.include` directives:

`as -I {{path/to/directory}} {{file.s}}`

