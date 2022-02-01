---
id: osx.automountd
title: Automountd
desc: ''
updated: 1643749505690
created: 1643749505690
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# automountd

> An automatic mount/unmount daemon for `autofs`. Started on demand by `launchd`.
> It should not be invoked manually.
> More information: <https://www.manpagez.com/man/8/automountd/>.

- Start the daemon:

`automountd`

- Log more details to `syslog`:

`automountd -v`

