---
id: common.nodenv
title: Nodenv
desc: ''
updated: 1623965306200
created: 1623965306200
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nodenv

> A tool to manage Node.js versions.
> More information: <https://github.com/nodenv/nodenv>.

- Install a specific version of Node.js:

`nodenv install {{version}}`

- Display a list of available versions:

`nodenv install --list`

- Use a specific version of Node.js across the whole system:

`nodenv global {{version}}`

- Use a specific version of Node.js with a directory:

`nodenv local {{version}}`

- Display the Node.js version for the current directory:

`nodenv version`

- Display the location of a Node.js installed command (e.g. `npm`):

`nodenv which {{command}}`

