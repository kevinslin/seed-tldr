---
id: common.virsh-help
title: Virsh Help
desc: ''
updated: 1623965016154
created: 1623965016154
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# virsh-help

> Display information about `virsh` commands or command groups.
> See also: `virsh`.
> More information: <https://manned.org/virsh>.

- List the `virsh` commands grouped into related categories:

`virsh help`

- List the command categories:

`virsh help | grep "keyword"`

- List the commands in a category:

`virsh help {{category_keyword}}`

- Show help for a command:

`virsh help {{command}}`

