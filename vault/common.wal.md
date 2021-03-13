---
id: common.wal
title: Wal
desc: ''
updated: 1615663978739
created: 1615663978739
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wal

> A tool to create color schemes based on the dominant colors of a wallpaper.
> More information: <https://github.com/dylanaraps/pywal>.

- Preview color scheme:

`wal --preview {{image.png}}`

- Create color scheme:

`wal -i {{image.png}}`

- Create a light color scheme:

`wal -il {{image.png}}`

- Skip setting the desktop wallpaper:

`wal -in {{image.png}}`

- Skip setting the terminal colors:

`wal -is {{image.png}}`

- Restore the previously generated color scheme and wallpaper:

`wal -R`

