---
id: common.ganache-cli
title: Ganache CLI
desc: ''
updated: 1642441815019
created: 1642441815019
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ganache-cli

> Command-line version of Ganache, your personal blockchain for Ethereum development.
> More information: <https://www.trufflesuite.com/ganache>.

- Run Ganache:

`ganache-cli`

- Run Ganache with a specific number of accounts:

`ganache-cli --accounts={{number_of_accounts}}`

- Run Ganache and lock available accounts by default:

`ganache-cli --secure`

- Run Ganache server and unlock specific accounts:

`ganache-cli --secure --unlock "{{account_private_key1}}" --unlock "{{account_private_key2}}"`

- Run Ganache with a specific account and balance:

`ganache-cli --account="{{account_private_key}},{{account_balance}}"`

- Run Ganache with accounts with a default balance:

`ganache-cli --defaultBalanceEther={{default_balance}}`

- Run Ganache and log all requests to stdout:

`ganache-cli --verbose`

