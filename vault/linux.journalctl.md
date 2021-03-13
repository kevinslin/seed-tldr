---
id: linux.journalctl
title: Journalctl
desc: ''
updated: 1615663978748
created: 1615663978748
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# journalctl

> Query the systemd journal.

- Show all messages from this boot:

`journalctl -b`

- Show all messages from last boot:

`journalctl -b -1`

- Show all messages with priority level 3 (errors) from this boot:

`journalctl -b --priority={{3}}`

- Follow new messages (like `tail -f` for traditional syslog):

`journalctl -f`

- Show all messages by a specific unit:

`journalctl -u {{unit}}`

- Filter messages within a time range (either timestamp or placeholders like "yesterday"):

`journalctl --since {{now|today|yesterday|tomorrow}} --until {{YYYY-MM-DD HH:MM:SS}}`

- Show all messages by a specific process:

`journalctl _PID={{pid}}`

- Show all messages by a specific executable:

`journalctl {{path/to/executable}}`

