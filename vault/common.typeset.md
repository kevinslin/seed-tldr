---
id: common.typeset
title: Typeset
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# typeset

> Declare variables and give them attributes.
> More information: <https://www.gnu.org/software/bash/manual/bash.html#Bash-Builtins>.

- Declare a string variable with the specified value:

`typeset {{variable}}="{{value}}"`

- Declare an integer variable with the specified value:

`typeset -i {{variable}}="{{value}}"`

- Declare an array variable with the specified value:

`typeset {{variable}}=({{item_a item_b item_c}})`

- Declare an associative array variable with the specified value:

`typeset -A {{variable}}=({{[key_a]=item_a [key_b]=item_b [key_c]=item_c}})`

- Declare a readonly variable with the specified value:

`typeset -r {{variable}}="{{value}}"`

- Declare a global variable within a function with the specified value:

`typeset -g {{variable}}="{{value}}"`

