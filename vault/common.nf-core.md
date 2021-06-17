---
id: common.nf-core
title: Nf Core
desc: ''
updated: 1623965306200
created: 1623965306200
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nf-core

> The nf-core framework tools, to create, check and develop best-practice guidelines for Nextflow.
> More information: <https://nf-co.re/tools>.

- List existing pipelines on nf-core:

`nf-core list`

- Create a new pipeline skeleton:

`nf-core create`

- Lint the pipeline code:

`nf-core lint {{path/to/directory}}`

- Bump software versions in pipeline recipe:

`nf-core bump-version {{path/to/directory}} {{new_version}}`

- Launch an nf-core pipeline:

`nf-core launch {{pipeline_name}}`

- Download an nf-core pipeline for offline use:

`nf-core download {{pipeline_name}}`

