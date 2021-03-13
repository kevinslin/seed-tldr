---
id: common.npx
title: Npx
desc: ''
updated: 1615663978727
created: 1615663978727
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# npx

> Execute binaries from `npm` packages.
> More information: <https://www.npmjs.com/package/npx>.

- Execute the binary from a given npm module:

`npx {{module_name}}`

- In case a package has multiple binaries, specify the package name along with the binary:

`npx -p {{package_name}} {{module_name}}`

- View help contents:

`npx --help`
