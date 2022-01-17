---
id: common.hardhat
title: Hardhat
desc: ''
updated: 1642441815032
created: 1642441815032
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hardhat

> A development environment for Ethereum software.
> More information: <https://hardhat.org>.

- List available subcommands (or create a new project if no configuration exists):

`hardhat`

- Compile the current project and build all artifacts:

`hardhat compile`

- Run a user-defined script after compiling the project:

`hardhat run {{path/to/script.js}}`

- Run Mocha tests:

`hardhat test`

- Run all given test files:

`hardhat test {{path/to/file1.js}} {{path/to/file2.js}}`

- Start a local Ethereum JSON-RPC node for development:

`hardhat node`

- Start a local Ethereum JSON-RPC node with a specific hostname and port:

`hardhat node --hostname {{hostname}} --port {{port}}`

- Clean the cache and all artifacts:

`hardhat clean`

