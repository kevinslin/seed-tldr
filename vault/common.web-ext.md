---
id: common.web-ext
title: Web Ext
desc: ''
updated: 1623965306216
created: 1623965306216
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# web-ext

> A command-line tool for managing web extension development.
> More information: <https://www.npmjs.com/package/web-ext>.

- Run the web extension in the current directory in Firefox:

`web-ext run`

- Run a web extension from a specific directory in Firefox:

`web-ext run --source-dir {{path/to/directory}}`

- Display verbose execution output:

`web-ext run --verbose`

- Run a web extension in Firefox Android:

`web-ext run --target firefox-android`

- Lint the manifest and source files for errors:

`web-ext lint`

- Build and package the extension:

`web-ext build`

- Display verbose build output:

`web-ext build --verbose`

- Sign a package for self-hosting:

`web-ext sign --api-key {{api_key}} --api-secret {{api_secret}}`

