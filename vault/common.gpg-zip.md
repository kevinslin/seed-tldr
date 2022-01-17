---
id: common.gpg-zip
title: Gpg Zip
desc: ''
updated: 1642441815030
created: 1642441815030
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gpg-zip

> Encrypt files and directories in an archive using GPG.
> More information: <https://www.gnupg.org/documentation/manuals/gnupg/gpg_002dzip.html>.

- Encrypt a directory into `archive.gpg` using a passphrase:

`gpg-zip --symmetric --output {{archive.gpg}} {{path/to/directory}}`

- Decrypt `archive.gpg` into a directory of the same name:

`gpg-zip --decrypt {{path/to/archive.gpg}}`

- List the contents of the encrypted `archive.gpg`:

`gpg-zip --list-archive {{path/to/archive.gpg}}`

