---
id: common.phpbu
title: Phpbu
desc: ''
updated: 1642441815057
created: 1642441815057
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phpbu

> A backup utility framework for PHP.
> More information: <https://phpbu.de>.

- Run backups using the default `phpbu.xml` configuration file:

`phpbu`

- Run backups using a specific configuration file:

`phpbu --configuration={{path/to/configuration_file.xml}}`

- Only run the specified backups:

`phpbu --limit={{backup_task_name}}`

- Simulate the actions that would have been performed:

`phpbu --simulate`

