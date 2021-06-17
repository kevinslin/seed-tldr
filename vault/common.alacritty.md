---
id: common.alacritty
title: Alacritty
desc: ''
updated: 1623965016111
created: 1623965016111
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# alacritty

> Cross-platform, GPU-accelerated terminal emulator.
> More information: <https://github.com/alacritty/alacritty>.

- Open a new Alacritty window:

`alacritty`

- Run in a specific directory:

`alacritty --working-directory {{path/to/directory}}`

- Run a command in a new Alacritty window:

`alacritty -e {{command}}`

- Specify alternative configuration file (defaults to `$XDG_CONFIG_HOME/alacritty/alacritty.yml`):

`alacritty --config-file {{path/to/config.yml}}`

- Run with live config reload enabled (can also be enabled by default in `alacritty.yml`):

`alacritty --live-config-reload --config-file {{path/to/config.yml}}`

