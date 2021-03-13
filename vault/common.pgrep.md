---
id: common.pgrep
title: Pgrep
desc: ''
updated: 1615663978729
created: 1615663978729
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pgrep

> Find or signal process by name.

- Return PIDs of any running processes with a matching command string:

`pgrep {{process_name}}`

- Search full command line with parameters instead of just the process name:

`pgrep -f "{{process_name}} {{parameter}}"`

- Search for process run by a specific user:

`pgrep -u root {{process_name}}`

