---
id: linux.goaccess
title: Goaccess
desc: ''
updated: 1642441815096
created: 1642441815096
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# goaccess

> An open source real-time web log analyzer.
> More information: <https://goaccess.io>.

- Analyze one or more log files in interactive mode:

`goaccess {{path/to/logfile1 path/to/file2 ...}}`

- Use a specific log-format (or pre-defined formats like "combined"):

`goaccess {{path/to/logfile}} --log-format={{format}}`

- Analyse a log from stdin:

`tail -f {{path/to/logfile}} | goaccess -`

- Analyze a log and write it to an HTML file in real-time:

`goaccess {{path/to/logfile}} --output {{path/to/file.html}} --real-time-html`

