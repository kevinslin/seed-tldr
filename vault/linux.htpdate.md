---
id: linux.htpdate
title: Htpdate
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# htpdate

> Synchronize local date and time via HTTP headers from web servers.
> More information: <http://www.vervest.org/htp/>.

- Synchronize date and time:

`sudo htpdate {{host}}`

- Perform simulation of synchronization, without any action:

`htpdate -q {{host}}`

- Compensate the systematisch clock drift:

`sudo htpdate -x {{host}}`

- Set time immediate after the synchronization:

`sudo htpdate -s {{host}}`

