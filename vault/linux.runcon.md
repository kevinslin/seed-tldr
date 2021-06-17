---
id: linux.runcon
title: Runcon
desc: ''
updated: 1623965306229
created: 1623965306229
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# runcon

> Run a program in a different SELinux security context.
> With neither context nor command, print the current security context.
> More information: <https://www.gnu.org/software/coreutils/runcon>.

- Determine the current domain:

`runcon`

- Specify the domain to run a command in:

`runcon -t {{domain}}_t {{command}}`

- Specify the context role to run a command with:

`runcon -r {{role}}_r {{command}}`

- Specify the full context to run a command with:

`runcon {{user}}_u:{{role}}_r:{{domain}}_t {{command}}`

