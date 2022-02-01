---
id: windows.pabcnetcclear
title: Pabcnetcclear
desc: ''
updated: 1642441815128
created: 1642441815128
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pabcnetcclear

> Preprocess and compile PascalABC.NET source files.
> More information: <http://pascalabc.net>.

- Compile a given source file into an executable with the same name:

`pabcnetcclear {{path/to/file.pas}}`

- Compile a given source file into an executable with the specified name:

`pabcnetcclear /Output:{{path/to/file.pas}} {{path/to/file.pas}}`

- Compile a given source file into an executable with the same name along with/without debug information:

`pabcnetcclear /Debug:{{0|1}} {{path/to/file.pas}}`

- Allow units to be searched in a path while compiling a given source file into an executable with the same name:

`pabcnetcclear /SearchDir:{{path/to/dir}} {{path/to/file.pas}}`

- Compile a given source file into an executable, defining a symbol:

`pabcnetcclear /Define:{{symbol}} {{path/to/file.pas}}`

