---
id: common.hg-serve
title: Hg Serve
desc: ''
updated: 1642441815033
created: 1642441815033
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hg serve

> Start a standalone Mercurial web server for browsing repositories.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#serve>.

- Start a web server instance:

`hg serve`

- Start a web server instance on the specified port:

`hg serve --port {{port}}`

- Start a web server instance on the specified listening address:

`hg serve --address {{address}}`

- Start a web server instance with a specific identifier:

`hg serve --name {{name}}`

- Start a web server instance using the specified theme (see the templates directory):

`hg serve --style {{style}}`

- Start a web server instance using the specified SSL certificate bundle:

`hg serve --certificate {{path/to/certificate}}`

