---
id: linux.disown
title: Disown
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# disown

> Allow sub-processes to live beyond the shell that they are attached to.
> See also the `jobs` command.
> More information: <https://www.gnu.org/software/bash/manual/bash.html#index-disown>.

- Disown the current job:

`disown`

- Disown a specific job:

`disown %{{job_number}}`

- Disown all jobs:

`disown -a`

- Keep job (do not disown it), but mark it so that no future SIGHUP is received on shell exit:

`disown -h %{{job_number}}`

