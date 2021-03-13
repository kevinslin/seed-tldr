---
id: common.tldrl
title: Tldrl
desc: ''
updated: 1615663978736
created: 1615663978736
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tldrl

> Lint and format `tldr` pages.
> More information: <https://github.com/tldr-pages/tldr-lint>.

- Lint all pages:

`tldrl {{pages_directory}}`

- Format a specific page to stdout:

`tldrl -f {{page.md}}`

- Format all pages in place:

`tldrl -fi {{pages_directory}}`

