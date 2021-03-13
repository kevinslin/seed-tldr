---
id: common.croc
title: Croc
desc: ''
updated: 1615655543049
created: 1615655543049
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

