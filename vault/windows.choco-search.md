---
id: windows.choco-search
title: Choco Search
desc: ''
updated: 1642441815126
created: 1642441815126
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

