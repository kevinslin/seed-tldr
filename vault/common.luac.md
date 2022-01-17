---
id: common.luac
title: Luac
desc: ''
updated: 1642441815045
created: 1642441815045
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# luac

> Lua bytecode compiler.
> More information: <https://www.lua.org>.

- Compile a Lua source file to Lua bytecode:

`luac -o {{byte_code.luac}} {{source.lua}}`

- Do not include debug symbols in the output:

`luac -s -o {{byte_code.luac}} {{source.lua}}`

