---
id: common.mcs
title: Mcs
desc: ''
updated: 1647684124138
created: 1647684124138
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mcs

> Mono C# Compiler.
> More information: <https://manned.org/mcs.1>.

- Compile the specified files:

`mcs {{path/to/input_file1.cs path/to/input_file2.cs ...}}`

- Specify the output program name:

`mcs -out:{{path/to/file.exe}} {{path/to/input_file1.cs path/to/input_file2.cs ...}}`

- Specify the output program type:

`mcs -target:{{exe|winexe|library|module}} {{path/to/input_file1.cs path/to/input_file2.cs ...}}`

