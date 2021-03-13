---
id: windows.choco-info
title: Choco Info
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# choco info

> Display detailed information about a package with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-info>.

- Display information on a specific package:

`choco info {{package}}`

- Display information for a local package only:

`choco info {{package}} --local-only`

- Specify a custom source to receive packages information from:

`choco info {{package}} --source {{source_url|alias}}`

- Provide a username and password for authentication:

`choco info {{package}} --user {{username}} --password {{password}}`

