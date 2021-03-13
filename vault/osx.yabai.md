---
id: osx.yabai
title: Yabai
desc: ''
updated: 1615663978762
created: 1615663978762
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# yabai

> A tiling window manager for macOS based on binary space partitioning.
> More information: <https://github.com/koekeishiya/yabai>.

- Set the layout to bsp:

`yabai -m config layout {{bsp}}`

- Set the window gap to 10pt:

`yabai -m config window_gap {{10}}`

- Enable opacity:

`yabai -m config window_opacity on`

- Disable window shadow:

`yabai -m config window_shadow off`

- Enable status bar:

`yabai -m config status_bar on`
