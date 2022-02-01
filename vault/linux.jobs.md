---
id: linux.jobs
title: Jobs
desc: ''
updated: 1642441815100
created: 1642441815100
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jobs

> BASH builtin for viewing information about processes spawned by the current shell.
> More information: <https://manned.org/jobs>.

- View jobs spawned by the current shell:

`jobs`

- List jobs and their process IDs:

`jobs -l`

- Display information about jobs with changed status:

`jobs -n`

- Display process ID of process group leader:

`jobs -p`

- Display running processes:

`jobs -r`

- Display stopped processes:

`jobs -s`

