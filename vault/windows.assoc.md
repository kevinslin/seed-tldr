---
id: windows.assoc
title: Assoc
desc: ''
updated: 1642441815126
created: 1642441815126
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# assoc

> Display or modify file extension associations.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/assoc>.

- Display all associated filetypes:

`assoc`

- Display the associated filetype for a specific extension:

`assoc {{.txt}}`

- Modify the associated filetype for a specific extension:

`assoc {{.txt}}={{txtfile}}`

