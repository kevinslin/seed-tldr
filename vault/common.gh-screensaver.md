---
id: common.gh-screensaver
title: Gh Screensaver
desc: ''
updated: 1642441815020
created: 1642441815020
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh screensaver

> Extension for GitHub CLI that runs animated terminal screensavers.
> See also: `gh extension`.
> More information: <https://github.com/vilmibm/gh-screensaver>.

- Run a random screensaver:

`gh screensaver`

- Run a specific screensaver:

`gh screensaver --saver {{fireworks|marquee|pipes|pollock|starfield}}`

- Run the "marquee" screensaver with a specific text and font:

`gh screensaver --saver {{marquee}} -- --message="{{message}}" --font={{font_name}}`

- Run the "starfield" screensaver with a specific density and speed:

`gh screensaver --saver {{starfield}} -- --density {{500}} --speed {{10}}`

- List available screensavers:

`gh screensaver --list`

