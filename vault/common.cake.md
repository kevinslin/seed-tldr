---
id: common.cake
title: Cake
desc: ''
updated: 1642441815000
created: 1642441815000
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cake

> The command-line processor for the CakePHP framework.
> More information: <https://cakephp.org>.

- Display basic information about the current app and available commands:

`cake`

- Display a list of available routes:

`cake routes`

- Clear configuration caches:

`cake cache clear_all`

- Build the metadata cache:

`cake schema_cache build --connection {{connection}}`

- Clear the metadata cache:

`cake schema_cache clear`

- Clear a single cache table:

`cake schema_cache clear {{table_name}}`

- Start a development web server (defaults to port 8765):

`cake server`

- Start a REPL (interactive shell):

`cake console`

