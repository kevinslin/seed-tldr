---
id: common.vela
title: Vela
desc: ''
updated: 1623965016154
created: 1623965016154
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vela

> Command-line tools for the Vela pipeline.
> More information: <https://go-vela.github.io/docs/cli/>.

- Trigger a pipeline to run from a Git branch, commit or tag:

`vela add deployment --org {{organization}} --repo {{repository_name}} --target {{environment}} --ref {{branch|commit|refs/tags/git_tag}} --description "{{deploy_description}}"`

- List deployments for a repository:

`vela get deployment --org {{organization}} --repo {{repository_name}}`

- Inspect a specific deployment:

`vela view deployment --org {{organization}} --repo {{repository_name}} --deployment {{deployment_number}}`

