---
id: common.progpilot
title: Progpilot
desc: ''
updated: 1642441815061
created: 1642441815061
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# progpilot

> A PHP static analysis tool for detecting security vulnerabilities.
> More information: <https://github.com/designsecurity/progpilot>.

- Analyse the current directory:

`progpilot`

- Analyse a specific file or directory:

`progpilot {{path/to/file_or_directory}}`

- Specify a custom configuration file:

`progpilot --configuration {{path/to/configuration.yml}}`

