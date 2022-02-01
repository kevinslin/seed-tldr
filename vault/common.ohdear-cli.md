---
id: common.ohdear-cli
title: Ohdear CLI
desc: ''
updated: 1642441815054
created: 1642441815054
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ohdear-cli

> An unofficial Oh Dear CLI written with Laravel Zero.
> More information: <https://github.com/nunomaduro/ohdear-cli>.

- Display details about the currently authenticated user:

`ohdear-cli me`

- Add a new site to Oh Dear:

`ohdear-cli sites:add {{url}}`

- Display a list of sites and their current status:

`ohdear-cli sites:list`

- Display details about a specific site:

`ohdear-cli sites:show {{site_id}}`

