---
id: common.avo
title: Avo
desc: ''
updated: 1642441814996
created: 1642441814996
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# avo

> The official command-line interface for Avo.
> More information: <https://www.avo.app/docs/implementation/cli>.

- Initialize a workspace in the current directory:

`avo init`

- Log into the Avo platform:

`avo login`

- Switch to an existing Avo branch:

`avo checkout {{branch_name}}`

- Pull analytics wrappers for the current path:

`avo pull`

- Display the status of the Avo implementation:

`avo status`

- Resolve Git conflicts in Avo files:

`avo conflict`

- Open the current Avo workspace in the default web browser:

`avo edit`

- Display help for a subcommand:

`avo {{subcommand}} --help`

