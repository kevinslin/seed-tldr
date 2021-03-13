---
id: windows.choco-search
title: Choco Search
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# choco search

> Search for a local or remote package with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-search>.

- Search for a package:

`choco search {{query}}`

- Search for a package locally:

`choco search {{query}} --local-only`

- Only include exact matches in the results:

`choco search {{query}} --exact`

- Confirm all prompts automatically:

`choco search {{query}} --yes`

- Specify a custom source to search for packages in:

`choco search {{query}} --source {{source_url|alias}}`

- Provide a username and password for authentication:

`choco search {{query}} --user {{username}} --password {{password}}`

