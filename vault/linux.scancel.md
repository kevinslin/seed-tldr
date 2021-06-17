---
id: linux.scancel
title: Scancel
desc: ''
updated: 1623965016168
created: 1623965016168
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scancel

> Cancel a Slurm job.
> More information: <https://slurm.schedmd.com/scancel.html>.

- Cancel a job using its ID:

`scancel {{job_id}}`

- Cancel all jobs from a user:

`scancel {{user_name}}`

