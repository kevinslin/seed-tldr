---
id: common.plenv
title: Plenv
desc: ''
updated: 1642441815060
created: 1642441815060
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# plenv

> Switch between multiple versions of Perl.
> More information: <https://github.com/tokuhirom/plenv>.

- Show the currently selected Perl version and how it was selected:

`plenv version`

- List all available installed Perl versions:

`plenv versions`

- Set the global Perl version (used unless a local or shell version takes priority):

`plenv global {{version}}`

- Set the local application-specific Perl version (used in the current directory and all directories below it):

`plenv local {{version}}`

- Set the shell-specific Perl version (used for the current session only):

`plenv shell {{version}}`

- Display help:

`plenv`

- Display help for a command:

`plenv help {{command}}`

