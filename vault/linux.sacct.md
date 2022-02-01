---
id: linux.sacct
title: Sacct
desc: ''
updated: 1642441815112
created: 1642441815112
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sacct

> Display accounting data from the Slurm service.
> More information: <https://slurm.schedmd.com/sacct.html>.

- Display job id, job name, partition, account, number of allocated cpus, job state, and job exit codes for recent jobs:

`sacct`

- Display job id, job state, job exit code for recent jobs:

`sacct --brief`

- Display the allocations of a job:

`sacct --jobs {{job_id}} --allocations`

- Display elapsed time, job name, number of requested CPUs, and memory requested of a job:

`sacct --jobs {{job_id}} --format={{elapsed}},{{jobname}},{{reqcpus}},{{reqmem}}`

