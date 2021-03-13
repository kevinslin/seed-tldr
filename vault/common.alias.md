---
id: common.alias
title: Alias
desc: ''
updated: 1615663978697
created: 1615663978697
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# alias

> Creates aliases -- words that are replaced by a command string.
> Aliases expire with the current shell session, unless they're defined in the shell's configuration file, e.g. `~/.bashrc`.

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

