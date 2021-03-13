---
id: linux.logsave
title: Logsave
desc: ''
updated: 1615663978749
created: 1615663978749
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# logsave

> Save the output of a command in a logfile.
> More information: <https://linux.die.net/man/8/logsave>.

- Execute command with specified argument(s) and save its output to log file:

`logsave {{path/to/logfile}} {{command}}`

- Take input from standard input and save it in a log file:

`logsave {{logfile}} -`

- Append the output to a log file, instead of replacing its current contents:

`logsave -a {{logfile}} {{command}}`

- Show verbose output:

`logsave -v {{logfile}} {{command}}`

