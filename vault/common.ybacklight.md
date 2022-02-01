---
id: common.ybacklight
title: Ybacklight
desc: ''
updated: 1642441815085
created: 1642441815085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ybacklight

> Manage screen backlight brightness. See also `xbacklight`.
> More information: <https://github.com/pixelcmtd/ybacklight>.

- Print current brightness and maximal brightness, shortened and separated by a slash:

`ybacklight Sc/Sm`

- Set the brightness to 420:

`ybacklight s{{420}}`

- Increase the brightness by 42 big steps (4200 by default):

`ybacklight Si{{42}}`

- Decrease the brightness by 300:

`ybacklight d{{300}}`

