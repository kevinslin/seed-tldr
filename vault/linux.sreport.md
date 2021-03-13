---
id: linux.sreport
title: Sreport
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

