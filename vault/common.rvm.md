---
id: common.rvm
title: Rvm
desc: ''
updated: 1615663978733
created: 1615663978733
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rvm

> A tool for easily installing, managing, and working with multiple ruby environments.
> More information: <https://rvm.io>.

- Install one or more space-separated versions of Ruby:

`rvm install {{version(s)}}`

- Display a list of installed versions:

`rvm list`

- Use a specific version of Ruby:

`rvm use {{version}}`

- Set the default Ruby version:

`rvm --default use {{version}}`

- Upgrade a version of Ruby to a new version:

`rvm upgrade {{current_version}} {{new_version}}`

- Uninstall a version of Ruby and keep its sources:

`rvm uninstall {{version}}`

- Remove a version of Ruby and its sources:

`rvm remove {{version}}`

- Show specific dependencies for your OS:

`rvm requirements`
