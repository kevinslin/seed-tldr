---
id: common.berks
title: Berks
desc: ''
updated: 1642441814998
created: 1642441814998
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# berks

> Chef cookbook dependency manager.
> More information: <https://docs.chef.io/berkshelf.html>.

- Install cookbook dependencies into a local repo:

`berks install`

- Update a specific cookbook and its dependencies:

`berks update {{cookbook}}`

- Upload a cookbook to the Chef server:

`berks upload {{cookbook}}`

- View the dependencies of a cookbook:

`berks contingent {{cookbook}}`

