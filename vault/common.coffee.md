---
id: common.coffee
title: Coffee
desc: ''
updated: 1623965306177
created: 1623965306177
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# coffee

> Executes CoffeeScript scripts or compiles them into JavaScript.
> More information: <https://coffeescript.org#cli>.

- Run a script:

`coffee {{path/to/file.coffee}}`

- Compile to JavaScript and save to a file with the same name:

`coffee --compile {{path/to/file.coffee}}`

- Compile to JavaScript and save to a given output file:

`coffee --compile {{path/to/file.coffee}} --output {{path/to/file.js}}`

- Run interactive REPL:

`coffee --interactive`

- Watch script for changes and re-run script:

`coffee --watch {{path/to/file.coffee}}`

