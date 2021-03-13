---
id: common.box
title: Box
desc: ''
updated: 1615655543046
created: 1615655543046
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# box

> A PHP application for building and managing Phars.
> More information: <https://github.com/box-project/box>.

- Compile a new Phar file:

`box compile`

- Compile a new Phar file using a specific config file:

`box compile -c {{path/to/config}}`

- Display information about the PHAR PHP extension:

`box info`

- Display information about a specific Phar file:

`box info {{path/to/phar_file}}`

- Validate the first found config file in the working directory:

`box validate`

- Verify the signature of a specific Phar file:

`box verify {{path/to/phar_file}}`

- Display all available commands and options:

`box help`

