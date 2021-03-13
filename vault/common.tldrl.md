---
id: common.tldrl
title: Tldrl
desc: ''
updated: 1615655543089
created: 1615655543089
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

