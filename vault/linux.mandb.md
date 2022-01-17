---
id: linux.mandb
title: Mandb
desc: ''
updated: 1642441815103
created: 1642441815103
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mandb

> Manage the pre-formatted manual page database.
> More information: <https://man7.org/linux/man-pages/man8/mandb.8.html>.

- Purge and process manual pages:

`mandb`

- Update a single entry:

`mandb --filename {{path/to/file}}`

- Create entries from scratch instead of updating:

`mandb --create`

- Only process user databases:

`mandb --user-db`

- Do not purge obsolete entries:

`mandb --no-purge`

- Check the validity of manual pages:

`mandb --test`

