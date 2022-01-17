---
id: common.shopt
title: Shopt
desc: ''
updated: 1642441815068
created: 1642441815068
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shopt

> Manage Bash shell options: variables (stored in `$BASHOPTS`) that control behavior specific to the Bash shell.
> Generic POSIX shell variables (stored in `$SHELLOPTS`) are managed with the `set` command instead.
> More information: <https://www.gnu.org/software/bash/manual/html_node/The-Shopt-Builtin.html>.

- List of all settable options and whether they are set:

`shopt`

- Set an option:

`shopt -s {{option_name}}`

- Unset an option:

`shopt -u {{option_name}}`

- Print a list of all options and their status formatted as runnable `shopt` commands:

`shopt -p`

- Show help for the command:

`help shopt`

