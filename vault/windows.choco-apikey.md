---
id: windows.choco-apikey
title: Choco Apikey
desc: ''
updated: 1623965306237
created: 1623965306237
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

