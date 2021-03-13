---
id: linux.trap
title: Trap
desc: ''
updated: 1615663978756
created: 1615663978756
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trap

> Automatically execute commands after receiving signals by processes or the operating system.
> Can be used to perform cleanups for interruptions by the user or other actions.

- List available signals to set traps for:

`trap -l`

- List active traps for the current shell:

`trap -p`

- Set a trap to execute commands when one or more signals are detected:

`trap 'echo "Caught signal {{SIGHUP}}"' {{SIGHUP}}`

- Remove active traps:

`trap - {{SIGHUP}} {{SIGINT}}`

