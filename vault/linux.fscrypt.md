---
id: linux.fscrypt
title: Fscrypt
desc: ''
updated: 1642441815095
created: 1642441815095
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fscrypt

> Go tool for managing Linux filesystem encryption.
> More information: <https://github.com/google/fscrypt>.

- Prepare the root filesystem for use with fscrypt:

`fscrypt setup`

- Enable filesystem encryption for a directory:

`fscrypt encrypt {{path/to/directory}}`

- Unlock an encrypted directory:

`fscrypt unlock {{path/to/encrypted_directory}}`

- Lock an encrypted directory:

`fscrypt lock {{path/to/encrypted_directory}}`

