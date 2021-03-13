---
id: common.luac
title: Luac
desc: ''
updated: 1615655543068
created: 1615655543068
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# luac

> Lua bytecode compiler.
> More information: <https://www.lua.org>.

- Compile a Lua source file to Lua bytecode:

`luac -o {{byte_code.luac}} {{source.lua}}`

- Do not include debug symbols in the output:

`luac -s -o {{byte_code.luac}} {{source.lua}}`

