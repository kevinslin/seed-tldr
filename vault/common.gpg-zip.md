---
id: common.gpg-zip
title: Gpg Zip
desc: ''
updated: 1615655543061
created: 1615655543061
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gpg-zip

> Encrypt files and directories in an archive using GPG.

- Encrypt a directory into `archive.gpg` using a passphrase:

`gpg-zip --symmetric --output {{archive.gpg}} {{path/to/directory}}`

- Decrypt `archive.gpg` into a directory of the same name:

`gpg-zip --decrypt {{path/to/archive.gpg}}`

- List the contents of the encrypted `archive.gpg`:

`gpg-zip --list-archive {{path/to/archive.gpg}}`

