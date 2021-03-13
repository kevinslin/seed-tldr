---
id: common.bg
title: Bg
desc: ''
updated: 1615655543046
created: 1615655543046
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# bg

> Resumes jobs that have been suspended (e.g. using `Ctrl + Z`), and keeps them running in the background.

- Resume most recently suspended job and run it in the background:

`bg`

- Resume a specific job (use `jobs -l` to get its ID) and run it in the background:

`bg %{{job_id}}`

