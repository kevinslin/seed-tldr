---
id: linux.xvfb-run
title: Xvfb Run
desc: ''
updated: 1623965306232
created: 1623965306232
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xvfb-run

> Run a command in a virtual X server environment.
> More information: <https://www.x.org/wiki/>.

- Run the specified command in a virtual X server:

`xvfb-run {{command}}`

- Try to get a free server number, if the default (99) is not available:

`xvfb-run --auto-servernum {{command}}`

- Pass arguments to the Xvfb server:

`xvfb-run --server-args "{{-screen 0 1024x768x24}}" {{command}}`

