---
id: common.lli
title: Lli
desc: ''
updated: 1642441815041
created: 1642441815041
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lli

> Directly execute programs from LLVM bitcode.
> More information: <https://www.llvm.org/docs/CommandGuide/lli.html>.

- Execute a bitcode or IR file:

`lli {{path/to/file.ll}}`

- Execute with command line arguments:

`lli {{path/to/file.ll}} {{argument1 argument2 ...}}`

- Enable all optimizations:

`lli -O3 {{path/to/file.ll}}`

- Load a dynamic library before linking:

`lli --dlopen={{path/to/library.dll}} {{path/to/file.ll}}`

