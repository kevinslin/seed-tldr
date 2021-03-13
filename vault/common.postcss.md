---
id: common.postcss
title: Postcss
desc: ''
updated: 1615655543079
created: 1615655543079
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# postcss

> PostCSS is a tool for transforming styles with JS plugins.
> More information: <https://postcss.org>.

- Parse and transform a CSS file:

`postcss {{path/to/file}}`

- Parse and transform a CSS file and output to a specific file:

`postcss {{path/to/file}} --output {{path/to/file}}`

- Parse and transform a CSS file and output to a specific directory:

`postcss {{path/to/file}} --dir {{path/to/directory}}`

- Parse and transform a CSS file in-place:

`postcss {{path/to/file}} --replace`

- Specify a custom PostCSS parser:

`postcss {{path/to/file}} --parser {{parser}}`

- Specify a custom PostCSS syntax:

`postcss {{path/to/file}} --syntax {{syntax}}`

- Watch for changes to a CSS file:

`postcss {{path/to/file}} --watch`

- Display available options and examples:

`postcss --help`

