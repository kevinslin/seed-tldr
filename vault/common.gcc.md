---
id: common.gcc
title: Gcc
desc: ''
updated: 1646222518216
created: 1646222518216
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gcc

> Preprocess and compile C and C++ source files, then assemble and link them together.
> More information: <https://gcc.gnu.org>.

- Compile multiple source files into executable:

`gcc {{path/to/source1.c path/to/source2.c ...}} --output {{path/to/output_executable}}`

- Allow warnings, debug symbols in output:

`gcc {{path/to/source.c}} -Wall -Og --output {{path/to/output_executable}}`

- Include libraries from a different path:

`gcc {{path/to/source.c}} --output {{path/to/output_executable}} -I{{path/to/header}} -L{{path/to/library}} -l{{library_name}}`

- Compile source code into Assembler instructions:

`gcc -S {{path/to/source.c}}`

- Compile source code without linking:

`gcc -c {{path/to/source.c}}`

