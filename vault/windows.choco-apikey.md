---
id: windows.choco-apikey
title: Choco Apikey
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# choco-apikey

> Manage API keys for Chocolatey sources.
> More information: <https://chocolatey.org/docs/commands-apikey>.

- Display a list of sources and their API keys:

`choco apikey`

- Display a specific source and its API key:

`choco apikey --source "{{source_url}}"`

- Set an API key for a source:

`choco apikey --source "{{source_url}}" --key "{{api_key}}"`

- Remove an API key for a source:

`choco apikey --source "{{source_url}}" --remove`

