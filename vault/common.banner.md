---
id: common.banner
title: Banner
desc: ''
updated: 1623965306175
created: 1623965306175
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# banner

> Print the given argument as a large ASCII art.
> More information: <https://man.archlinux.org/man/banner.1>.

- Print the text message as a large banner (quotes are optional):

`banner "{{Hello World}}"`

- Print the text message as a banner with a width of 50 characters:

`banner -w {{50}} "{{Hello World}}"`

- Read text from stdin:

`banner`

