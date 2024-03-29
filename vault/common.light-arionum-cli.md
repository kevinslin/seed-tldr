---
id: common.light-arionum-cli
title: Light Arionum CLI
desc: ''
updated: 1642441815041
created: 1642441815041
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# light-arionum-cli

> The PHP light wallet for the Arionum cryptocurrency.
> More information: <https://github.com/arionum/lightWalletCLI>.

- Generate a new public/private key pair:

`light-arionum-cli`

- Display the balance of the current address:

`light-arionum-cli balance`

- Display the balance of the specified address:

`light-arionum-cli balance {{address}}`

- Send a transaction with an optional message:

`light-arionum-cli send {{address}} {{value}} {{optional_message}}`

- Export the current wallet information:

`light-arionum-cli export`

- Display information about the current block:

`light-arionum-cli block`

- Display information about the current address' transactions:

`light-arionum-cli transactions`

- Display information about a specific transaction:

`light-arionum-cli transaction {{transaction_id}}`

