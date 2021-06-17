---
id: common.dcg
title: Dcg
desc: ''
updated: 1623965016118
created: 1623965016118
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dcg

> Drupal code generator.
> More information: <https://github.com/Chi-teck/drupal-code-generator>.

- Start a wizard to choose what kind of code (e.g. module, service, form, etc.) to generate:

`dcg`

- Directly specify the kind of code to generate:

`dcg {{service|plugin|theme|module|form}}`

- Generate the code in a specific directory:

`dcg --directory {{path/to/directory}}`

