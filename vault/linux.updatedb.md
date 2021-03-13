---
id: linux.updatedb
title: Updatedb
desc: ''
updated: 1615663978757
created: 1615663978757
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# updatedb

> Create or update the database used by `locate`.
> It is usually run daily by cron.

- Refresh database content:

`sudo updatedb`

- Display file names as soon as they are found:

`sudo updatedb --verbose`
