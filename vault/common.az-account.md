---
id: common.az-account
title: Az Account
desc: ''
updated: 1642441814997
created: 1642441814997
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az account

> Manage Azure subscription information.
> Part of `az`, the command-line client for Microsoft Azure.
> More information: <https://docs.microsoft.com/cli/azure/account>.

- Print a list of subscriptions for the logged in account:

`az account list`

- Set a `subscription` to be the currently active subscription:

`az account set --subscription {{subscription_id}}`

- List supported regions for the currently active subscription:

`az account list-locations`

- Print an access token to be used with `MS Graph API`:

`az account get-access-token --resource-type {{ms-graph}}`

- Print details of the currently active subscription in a specific format:

`az account show --output {{json|tsv|table|yaml}}`

