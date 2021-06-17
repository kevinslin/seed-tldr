---
id: linux.logger
title: Logger
desc: ''
updated: 1623965016163
created: 1623965016163
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# logger

> Add messages to syslog (/var/log/syslog).

- Log a message to syslog:

`logger {{message}}`

- Take input from stdin and log to syslog:

`echo {{log_entry}} | logger`

- Send the output to a remote syslog server running at a given port. Default port is 514:

`echo {{log_entry}} | logger --server {{hostname}} --port {{port}}`

- Use a specific tag for every line logged. Default is the name of logged in user:

`echo {{log_entry}} | logger --tag {{tag}}`

- Log messages with a given priority. Default is `user.notice`. See `man logger` for all priority options:

`echo {{log_entry}} | logger --priority {{user.warning}}`

