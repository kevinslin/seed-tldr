---
id: linux.jobs
title: Jobs
desc: ''
updated: 1615663978748
created: 1615663978748
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jobs

> BASH builtin for viewing information about processes spawned by the current shell.

- View jobs spawned by the current shell:

`jobs`

- List jobs and their process ids:

`jobs -l`

- Display information about jobs with changed status:

`jobs -n`

- Display process id of process group leader:

`jobs -p`

- Display running processes:

`jobs -r`

- Display stopped processes:

`jobs -s`

