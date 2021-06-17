---
id: common.croc
title: Croc
desc: ''
updated: 1623965306178
created: 1623965306178
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# croc

> Send and receive files easily and securely over any network.
> More information: <https://github.com/schollz/croc>.

- Send a file or directory:

`croc send {{path/to/file_or_directory}}`

- Send a file or directory with a specific passphrase:

`croc send --code {{passphrase}} {{path/to/file_or_directory}}`

- Receive a file or directory on receiving machine:

`croc {{passphrase}}`

- Send and connect over a custom relay:

`croc --relay {{ip_to_relay}} send {{path/to/file_or_directory}}`

- Receive and connect over a custom relay:

`croc --relay {{ip_to_relay}} {{passphrase}}`

- Host a croc relay on the default ports:

`croc relay`

- Display parameters and options for a croc command:

`croc {{send|relay}} --help`

