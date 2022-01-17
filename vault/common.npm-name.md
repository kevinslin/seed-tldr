---
id: common.npm-name
title: Npm Name
desc: ''
updated: 1642441815052
created: 1642441815052
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# npm-name

> Check whether a package or organization name is available on npm.
> More information: <https://github.com/sindresorhus/npm-name-cli>.

- Check if a specific package name is available in the npm registry:

`npm-name {{package}}`

- Find similar package names in the npm registry:

`npm-name --similar {{package}}`

