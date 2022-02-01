---
id: common.llvm-config
title: Llvm Config
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
# llvm-config

> Get various configuration information needed to compile programs which use LLVM.
> Typically called from build systems, like in Makefiles or configure scripts.
> More information: <https://llvm.org/docs/CommandGuide/llvm-config.html>.

- Compile and link an LLVM based program:

`clang++ $(llvm-config --cxxflags --ldflags --libs) --output {{path/to/output_executable}} {{path/to/source.cc}}`

- Print the `PREFIX` of your LLVM installation:

`llvm-config --prefix`

- Print all targets supported by your LLVM build:

`llvm-config --targets-built`

