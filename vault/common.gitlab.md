---
id: common.gitlab
title: GitLab
desc: ''
updated: 1642441815028
created: 1642441815028
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gitlab

> Ruby wrapper and CLI for the GitLab API.
> Some subcommands such as `gitlab ctl` have their own usage documentation.
> More information: <https://narkoz.github.io/gitlab/>.

- Create a new project:

`gitlab create_project {{project_name}}`

- Get info about a specific commit:

`gitlab commit {{project_name}} {{commit_hash}}`

- Get info about jobs in a CI pipeline:

`gitlab pipeline_jobs {{project_name}} {{pipeline_id}}`

- Start a specific CI job:

`gitlab job_play {{project_name}} {{job_id}}`

