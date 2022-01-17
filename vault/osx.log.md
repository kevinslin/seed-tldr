---
id: osx.log
title: Log
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# log

> View, export, and configure logging systems.
> More information: <https://www.dssw.co.uk/reference/log.html>.

- Stream live system logs:

`log stream`

- Stream logs sent to `syslog` from the process with a specific PID:

`log stream --process {{process_id}}`

- Show logs sent to syslog from a process with a specific name:

`log show --predicate "process == '{{process_name}}'"`

- Export all logs to disk for the past hour:

`sudo log collect --last {{1h}} --output {{path/to/file.logarchive}}`

