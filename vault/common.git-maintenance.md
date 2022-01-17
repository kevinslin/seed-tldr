---
id: common.git-maintenance
title: Git Maintenance
desc: ''
updated: 1642441815025
created: 1642441815025
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git-maintenance

> Run tasks to optimize Git repository data.
> More information: <https://git-scm.com/docs/git-maintenance>.

- Register the current repository in the user's list of repositories to daily have maintenance run:

`git maintenance register`

- Start running maintenance on the current repository:

`git maintenance start`

- Halt the background maintenance schedule for the current repository:

`git maintenance stop`

- Remove the current repository from the user's maintenance repository list:

`git maintenance unregister`

- Run a specific maintenance task on the current repository:

`git maintenance run --task={{commit-graph|gc|incremental-repack|loose-objects|pack-refs|prefetch}}`

