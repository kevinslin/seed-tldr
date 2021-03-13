---
id: osx.feh
title: Feh
desc: ''
updated: 1615663978759
created: 1615663978759
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# feh

> Lightweight image viewing utility.

- View images locally or using a URL:

`feh {{path/to/images}}`

- View images recursively:

`feh --recursive {{path/to/images}}`

- View images without window borders:

`feh --borderless {{path/to/images}}`

- Exit after the last image:

`feh --cycle-once {{path/to/images}}`

- Set the slideshow cycle delay:

`feh --slideshow-delay {{seconds}} {{path/to/images}}`

- Set your wallpaper (centered, filled, maximized, scaled or tiled):

`feh --bg-{{center|fill|max|scale|tile}} {{path/to/image}}`

