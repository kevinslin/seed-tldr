---
id: common.x11docker
title: X11docker
desc: ''
updated: 1623965306216
created: 1623965306216
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# x11docker

> Securely run GUI applications and desktop UIs in Docker containers.
> See also `xephyr`.
> More information: <https://github.com/mviereck/x11docker>.

- Launch VLC in a container:

`x11docker --pulseaudio --share={{$HOME/Videos}} {{jess/vlc}}`

- Launch Xfce in a window:

`x11docker --desktop {{x11docker/xfce}}`

- Launch GNOME in a window:

`x11docker --desktop --gpu --init={{systemd}} {{x11docker/gnome}}`

- Launch KDE Plasma in a window:

`x11docker --desktop --gpu --init={{systemd}} {{x11docker/kde-plasma}}`

- Display help:

`x11docker --help`

