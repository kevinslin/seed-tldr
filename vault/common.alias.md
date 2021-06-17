---
id: common.alias
title: Alias
desc: ''
updated: 1623965306172
created: 1623965306172
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# alias

> Creates aliases -- words that are replaced by a command string.
> Aliases expire with the current shell session unless defined in the shell's configuration file, e.g. `~/.bashrc`.
> More information: <https://tldp.org/LDP/abs/html/aliases.html>.

- List all aliases:

`alias`

- Create a generic alias:

`alias {{word}}="{{command}}"`

- View the command associated to a given alias:

`alias {{word}}`

- Remove an aliased command:

`unalias {{word}}`

- Turn `rm` into an interactive command:

`alias {{rm}}="{{rm -i}}"`

- Create `la` as a shortcut for `ls -a`:

`alias {{la}}="{{ls -a}}"`

