---
id: common.browser-sync
title: Browser Sync
desc: ''
updated: 1642441814999
created: 1642441814999
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# browser-sync

> Starts local web server that updates browser on file changes.
> More information: <https://browsersync.io/docs/command-line>.

- Start a server from a specific directory:

`browser-sync start --server {{path/to/directory}} --files {{path/to/directory}}`

- Start a server from local directory, watching all CSS files in a directory:

`browser-sync start --server --files '{{path/to/directory/*.css}}'`

- Create configuration file:

`browser-sync init`

- Start browser-sync from config file:

`browser-sync start --config {{config_file}}`

