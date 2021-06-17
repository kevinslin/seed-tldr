---
id: windows.choco-list
title: Choco List
desc: ''
updated: 1623965306237
created: 1623965306237
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# choco list

> Display a list of packages with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-list>.

- Display all available packages:

`choco list`

- Display all locally installed packages:

`choco list --local-only`

- Display a list including local programs:

`choco list --include-programs`

- Display only approved packages:

`choco list --approved-only`

- Specify a custom source to display packages from:

`choco list --source {{source_url|alias}}`

- Provide a username and password for authentication:

`choco list --user {{username}} --password {{password}}`

