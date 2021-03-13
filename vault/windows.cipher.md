---
id: windows.cipher
title: Cipher
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# cipher

> Encrypt or decrypt files on NTFS drives.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/cipher>.

- Encrypt a file or directory:

`cipher /e:{{path/to/file_or_directory}}`

- Decrypt a file or directory:

`cipher /d:{{path/to/file_or_directory}}`

- Securely remove a file or directory:

`cipher /w:{{path/to/file_or_directory}}`

