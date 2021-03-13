---
id: common.bg
title: Bg
desc: ''
updated: 1615663978700
created: 1615663978700
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bg

> Resumes jobs that have been suspended (e.g. using `Ctrl + Z`), and keeps them running in the background.

- Resume most recently suspended job and run it in the background:

`bg`

- Resume a specific job (use `jobs -l` to get its ID) and run it in the background:

`bg %{{job_id}}`

