---
id: common.swig
title: Swig
desc: ''
updated: 1642441815074
created: 1642441815074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# swig

> Generate bindings between C / C++ code and various high level languages such as JavaScript, Python, C#, and more.
> It uses special .i or .swg files to generate the bindings (C/C++ with SWIG directives, then outputs a C/C++ file that contains all the wrapper code needed to build an extension module.

- Generate a binding between C++ and Python:

`swig -c++ -python -o {{path/to/output_wrapper.cpp}} {{path/to/swig_file.i}}`

- Generate a binding between C++ and Go:

`swig -go -cgo -intgosize 64 -c++ {{path/to/swig_file.i}}`

- Generate a binding between C and Java:

`swig -java {{path/to/swig_file.i}}`

- Generate a binding between C and Ruby and prefix the Ruby module with {{foo::bar::}}:

`swig -ruby -prefix "{{foo::bar::}}" {{path/to/swig_file.i}}`

