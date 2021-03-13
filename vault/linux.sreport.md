---
id: linux.sreport
title: Sreport
desc: ''
updated: 1615663978756
created: 1615663978756
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

- Show users with highest cpu time use:

`sreport user topuser`

