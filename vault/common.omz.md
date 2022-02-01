---
id: common.omz
title: Omz
desc: ''
updated: 1642441815054
created: 1642441815054
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# omz

> Oh My Zsh command-line tool.
> More information: <https://github.com/ohmyzsh/ohmyzsh>.

- Update Oh My Zsh:

`omz update`

- Print the changes from the latest update of Oh My Zsh:

`omz changelog`

- Restart the current Zsh session and Oh My Zsh:

`omz reload`

- List all available plugins:

`omz plugin list`

- Enable/Disable an Oh My Zsh plugin:

`omz plugin {{enable|disable}} {{plugin}}`

- List all available themes:

`omz theme list`

- Set an Oh My Zsh theme in `~/.zshrc`:

`omz theme set {{theme}}`

