---
id: common.truffle
title: Truffle
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# truffle

> A tool for developing smart contracts for running services on the Ethereum blockchain.
> More information: <https://www.trufflesuite.com/docs/truffle/reference/truffle-commands>.

- Download a pre-built Truffle project (Truffle Box):

`truffle unbox {{box_name}}`

- Compile contract source files in the current directory:

`truffle compile`

- Run JavaScript and Solidity tests:

`truffle test`

- Run migrations to deploy contracts:

`truffle migrate`

- Display help for a subcommand:

`truffle help {{subcommand}}`

