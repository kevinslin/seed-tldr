---
id: linux.udevadm
title: Udevadm
desc: ''
updated: 1642441815115
created: 1642441815115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# udevadm

> Linux `udev` management tool.
> More information: <https://www.freedesktop.org/software/systemd/man/udevadm>.

- Monitor all device events:

`sudo udevadm monitor`

- Print `uevents` sent out by the kernel:

`sudo udevadm monitor --kernel`

- Print device events after being processed by `udev`:

`sudo udevadm monitor --udev`

- List attributes of a device:

`sudo udevadm info --attribute-walk --path {{/dev/sda1}}`

- Reload all `udev` rules:

`sudo udevadm control --reload-rules`

- Trigger all `udev` rules to run:

`sudo udevadm trigger`

