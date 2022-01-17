---
id: common.gh-run
title: Gh Run
desc: ''
updated: 1642441815020
created: 1642441815020
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh run

> View, run and watch recent GitHub Actions workflow runs.
> More information: <https://cli.github.com/manual/gh_run>.

- Interactively select a run to see information about the jobs:

`gh run view`

- Display information about a specific run:

`gh run view {{workflow_run_number}}`

- Display information about the steps of a job:

`gh run view --job={{job_number}}`

- Display the log of a job:

`gh run view --job={{job_number}} --log`

- Check a specific workflow and exit with a non-zero status if the run failed:

`gh run view {{workflow_run_number}} --exit-status && {{echo "run pending or passed"}}`

- Interactively select an active run and wait until it's done:

`gh run watch`

- Display the jobs for a run and wait until it's done:

`gh run watch {{workflow_run_number}}`

- Re-run a specific workflow:

`gh run rerun {{workflow_run_number}}`

