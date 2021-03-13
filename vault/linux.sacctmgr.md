---
id: linux.sacctmgr
title: Sacctmgr
desc: ''
updated: 1615663978755
created: 1615663978755
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sacctmgr

> View, setup, and manage Slurm accounts.
> More information: <https://slurm.schedmd.com/sacctmgr.html>.

- Show current configuration:

`sacctmgr show configuration`

- Add a cluster to the slurm database:

`sacctmgr add cluster {{cluster_name}}`

- Add an account to the slurm database:

`sacctmgr add account {{account_name}} cluster={{cluster_of_account}}`

- Show details of user/association/cluster/account:

`sacctmgr show {{user/association/cluster/account}}`

