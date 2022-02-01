---
id: osx.emond
title: Emond
desc: ''
updated: 1642441815120
created: 1642441815120
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# emond

> Event Monitor service that accepts events from various services, runs them through a simple rules engine, and takes action.
> The actions can run commands, send email, or SMS messages.
> More information: <https://www.xorrior.com/emond-persistence/>.

- Start the daemon:

`emond`

- Specify rules for emond to process by giving a path to a file or directory:

`emond -r {{path/to/file_or_directory}}`

- Use a specific configuration file:

`emond -c {{path/to/config}}`

