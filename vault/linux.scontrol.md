---
id: linux.scontrol
title: Scontrol
desc: ''
updated: 1623965306229
created: 1623965306229
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scontrol

> View information about and modify jobs.
> More information: <https://slurm.schedmd.com/scontrol.html>.

- Show information for job:

`scontrol show job {{job_id}}`

- Suspend a comma-separated list of running jobs:

`scontrol suspend {{job_id}}`

- Resume a comma-separated list of suspended jobs:

`scontrol resume {{job_id}}`

- Hold a comma-separated list of queued jobs (Use `release` command to permit the jobs to be scheduled):

`scontrol hold {{job_id}}`

- Release a comma-separated list of suspended job:

`scontrol release {{job_id}}`

