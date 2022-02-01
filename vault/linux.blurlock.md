---
id: linux.blurlock
title: Blurlock
desc: ''
updated: 1642441815089
created: 1642441815089
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# blurlock

> A simple wrapper around the i3 screen locker `i3lock`, which blurs the screen.
> See also: `i3lock`.
> More information: <https://gitlab.manjaro.org/packages/community/i3/i3exit/-/blob/master/blurlock>.

- Lock the screen to a blurred screenshot of the current screen:

`blurlock`

- Lock the screen and disable the unlock indicator (removes feedback on keypress):

`blurlock --no-unlock-indicator`

- Lock the screen and don't hide the mouse pointer:

`blurlock --pointer {{default}}`

- Lock the screen and show the number of failed login attempts:

`blurlock --show-failed-attempts`

