---
id: common.adscript
title: Adscript
desc: ''
updated: 1642441814992
created: 1642441814992
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# adscript

> Compiler for Adscript files.
> More information: <https://github.com/Amplus2/Adscript>.

- Compile a file to an object file:

`adscript --output {{path/to/file.o}} {{path/to/input_file.adscript}}`

- Compile and link a file to a standalone executable:

`adscript --executable --output {{path/to/file}} {{path/to/input_file.adscript}}`

- Compile a file to LLVM IR instead of native machine code:

`adscript --llvm-ir --output {{path/to/file.ll}} {{path/to/input_file.adscript}}`

- Cross-compile a file to an object file for a foreign CPU architecture or operating system:

`adscript --target-triple {{i386-linux-elf}} --output {{path/to/file.o}} {{path/to/input_file.adscript}}`

