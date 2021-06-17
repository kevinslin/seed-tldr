---
id: windows.cipher
title: Cipher
desc: ''
updated: 1623965016176
created: 1623965016176
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

