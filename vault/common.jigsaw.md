---
id: common.jigsaw
title: Jigsaw
desc: ''
updated: 1642441815037
created: 1642441815037
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jigsaw

> A Laravel-based static site builder for PHP.
> More information: <https://jigsaw.tighten.co>.

- Initialise a project:

`jigsaw init`

- Initialise a project using a starter template:

`jigsaw init {{template_name}}`

- Build the site for development:

`jigsaw build`

- Preview the site from the "build_local" directory:

`jigsaw serve`

- Build the site for production:

`jigsaw build production`

- Preview the site from the "build_production" directory:

`jigsaw serve {{build_production}}`

