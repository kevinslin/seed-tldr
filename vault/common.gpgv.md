---
id: common.gpgv
title: Gpgv
desc: ''
updated: 1615655543061
created: 1615655543061
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gpgv

> Verify OpenPGP signatures.
> More information: <https://www.gnupg.org/documentation/manuals/gnupg/gpgv.html>.

- Verify a signed file:

`gpgv {{path/to/file}}`

- Verify a signed file using a detached signature:

`gpgv {{path/to/signature}} {{path/to/file}}`

- Add a file to the list of keyrings (a single exported key also counts as a keyring):

`gpgv --keyring {{./alice.keyring}} {{path/to/signature}} {{path/to/file}}`

