---
id: common.ncc
title: Ncc
desc: ''
updated: 1642441815050
created: 1642441815050
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ncc

> Compile a Node.js application into a single file.
> Supports TypeScript, binary addons and dynamic requires.
> More information: <https://github.com/vercel/ncc>.

- Bundle a Node.js application:

`ncc build {{path/to/file.js}}`

- Bundle and minify a Node.js application:

`ncc build --minify {{path/to/file.js}}`

- Bundle and minify a Node.js application and generate source maps:

`ncc build --source-map {{path/to/file.js}}`

- Automatically recompile on changes to source files:

`ncc build --watch {{path/to/file.js}}`

- Bundle a Node.js application into a temporary directory and run it for testing:

`ncc run {{path/to/file.js}}`

- Clean the `ncc` cache:

`ncc clean cache`

