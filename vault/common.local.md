---
id: common.local
title: Local
desc: ''
updated: 1642441815042
created: 1642441815042
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# local

> Declare local variables and give them attributes.
> More information: <https://www.gnu.org/software/bash/manual/bash.html#Bash-Builtins>.

- Declare a string variable with the specified value:

`local {{variable}}="{{value}}"`

- Declare an integer variable with the specified value:

`local -i {{variable}}="{{value}}"`

- Declare an array variable with the specified value:

`local {{variable}}=({{item_a item_b item_c}})`

- Declare an associative array variable with the specified value:

`local -A {{variable}}=({{[key_a]=item_a [key_b]=item_b [key_c]=item_c}})`

- Declare a readonly variable with the specified value:

`local -r {{variable}}="{{value}}"`

