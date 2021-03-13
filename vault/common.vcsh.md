---
id: common.vcsh
title: Vcsh
desc: ''
updated: 1615655543091
created: 1615655543091
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# vcsh

> Version Control System for the home directory using Git repositories.
> More information: <https://github.com/RichiH/vcsh>.

- Initialize an (empty) repository:

`vcsh init {{repository_name}}`

- Clone a repository into a custom directory name:

`vcsh clone {{git_url}} {{repository_name}}`

- List all managed repositories:

`vcsh list`

- Execute a Git command on a managed repository:

`vcsh {{repository_name}} {{git_command}}`

- Push/pull all managed repositories to/from remotes:

`vcsh {{push|pull}}`

- Write a custom `.gitignore` file for a managed repository:

`vcsh write-gitignore {{repository_name}}`

