---
id: linux.sreport
title: Sreport
desc: ''
updated: 1642441815113
created: 1642441815113
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sreport

> Generate reports on jobs, users, and clusters from accounting data.
> More information: <https://slurm.schedmd.com/sreport.html>.

- Show pipe delimited cluster utilization data:

`sreport --parsable cluster utilization`

- Show number of jobs run:

`sreport job sizes printjobcount`

- Show users with the highest CPU time use:

`sreport user topuser`

