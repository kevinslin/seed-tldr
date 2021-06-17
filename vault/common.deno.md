---
id: common.deno
title: Deno
desc: ''
updated: 1623965306179
created: 1623965306179
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# deno

> A secure runtime for JavaScript and TypeScript.
> More information: <https://deno.land/>.

- Run a JavaScript or TypeScript file:

`deno run {{path/to/file.ts}}`

- Start a REPL (interactive shell):

`deno`

- Run a file with network access enabled:

`deno run --allow-net {{path/to/file.ts}}`

- Run a file from a URL:

`deno run {{https://deno.land/std/examples/welcome.ts}}`

- Install an executable script from a URL:

`deno install {{https://deno.land/std/examples/colors.ts}}`

