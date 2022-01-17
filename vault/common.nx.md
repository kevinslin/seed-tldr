---
id: common.nx
title: Nx
desc: ''
updated: 1642441815052
created: 1642441815052
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nx

> CLI utility for managing `nx` workspaces.
> More information: <https://nx.dev/l/r/getting-started/nx-cli>.

- Build a specific project:

`nx build {{project}}`

- Test a specific project:

`nx test {{project}}`

- Execute a target on a specific project:

`nx run {{project}}:{{target}}`

- Execute a target on multiple projects:

`nx run-many --target {{target}} --projects {{project1}},{{project2}}`

- Execute a target on all projects in the workspace:

`nx run-many --target {{target}} --all`

- Execute a target only on projects that have been changed:

`nx affected --target {{target}}`

