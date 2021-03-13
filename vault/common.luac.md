---
id: common.luac
title: Luac
desc: ''
updated: 1615663978722
created: 1615663978722
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

