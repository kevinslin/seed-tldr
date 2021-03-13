---
id: common.exec
title: Exec
desc: ''
updated: 1615663978708
created: 1615663978708
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# exec

> Replace the current process with another process.

- Replace with the specified command using the current environment variables:

`exec {{command -with -flags}}`

- Replace with the specified command, clearing environment variables:

`exec -c {{command -with -flags}}`

- Replace with the specified command and login using the default shell:

`exec -l {{command -with -flags}}`

- Replace with the specified command and change the process name:

`exec -a {{process_name}} {{command -with -flags}}`

