---
id: sunos.prctl
title: Prctl
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# prctl

> Get or set the resource controls of running processes,.
> Tasks, and projects.

- Examine process limits and permissions:

`prctl {{PID}}`

- Examine process limits and permissions in machine parseable format:

`prctl -P {{PID}}`

- Get specific limit for a running process:

`prctl -n process.max-file-descriptor {{PID}}`

