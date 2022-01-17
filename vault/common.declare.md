---
id: common.declare
title: Declare
desc: ''
updated: 1642441815007
created: 1642441815007
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# declare

> Declare variables and give them attributes.
> More information: <https://www.gnu.org/software/bash/manual/bash.html#Bash-Builtins>.

- Declare a string variable with the specified value:

`declare {{variable}}="{{value}}"`

- Declare an integer variable with the specified value:

`declare -i {{variable}}="{{value}}"`

- Declare an array variable with the specified value:

`declare -a {{variable}}=({{item_a item_b item_c}})`

- Declare an associative array variable with the specified value:

`declare -A {{variable}}=({{[key_a]=item_a [key_b]=item_b [key_c]=item_c}})`

- Declare a readonly string variable with the specified value:

`declare -r {{variable}}="{{value}}"`

- Declare a global variable within a function with the specified value:

`declare -g {{variable}}="{{value}}"`

