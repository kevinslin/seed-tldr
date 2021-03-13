---
id: linux.lastcomm
title: Lastcomm
desc: ''
updated: 1615655543103
created: 1615655543103
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# lastcomm

> Show last commands executed.
> More information: <https://manpages.debian.org/stable/acct/lastcomm.1.en.html>.

- Print information about all of the commands in the acct (record file):

`lastcomm`

- Display commands executed by a given user:

`lastcomm --user {{user}}`

- Display information about a given command executed on the system:

`lastcomm --command {{command}}`

- Display information about commands executed on a given terminal:

`lastcomm --tty {{terminal_name}}`

