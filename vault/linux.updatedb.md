---
id: linux.updatedb
title: Updatedb
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
# updatedb

> Create or update the database used by `locate`.
> It is usually run daily by cron.
> More information: <https://manned.org/updatedb>.

- Refresh database content:

`sudo updatedb`

- Display file names as soon as they are found:

`sudo updatedb --verbose`

