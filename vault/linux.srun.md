---
id: linux.srun
title: Srun
desc: ''
updated: 1623965306230
created: 1623965306230
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# srun

> Create an interactive slurm job or connect to an existing job.
> More information: <https://slurm.schedmd.com/srun.html>.

- Submit a basic interactive job:

`srun --pty /bin/bash`

- Submit an interactive job with different attributes:

`srun --ntasks-per-node={{num_cores}} --mem-per-cpu={{memory_MB}} --pty /bin/bash`

- Connect to a worker node with a job running:

`srun --jobid={{job_id}} --pty /bin/bash`

