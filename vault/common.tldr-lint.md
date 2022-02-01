---
id: common.tldr-lint
title: Tldr Lint
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tldr-lint

> Lint and format `tldr` pages.
> More information: <https://github.com/tldr-pages/tldr-lint>.

- Lint all pages:

`tldr-lint {{pages_directory}}`

- Format a specific page to stdout:

`tldr-lint --format {{page.md}}`

- Format all pages in place:

`tldr-lint --format --in-place {{pages_directory}}`

