---
id: common.gpg
title: Gpg
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
# gpg

> GNU Privacy Guard.
> See `gpg2` for GNU Privacy Guard 2.
> More information: <https://gnupg.org>.

- Create a GPG public and private key interactively:

`gpg --full-generate-key`

- Sign `doc.txt` without encryption (writes output to `doc.txt.asc`):

`gpg --clearsign {{doc.txt}}`

- Encrypt `doc.txt` for [alice@example.com](mailto:alice@example.com) (output to `doc.txt.gpg`):

`gpg --encrypt --recipient {{alice@example.com}} {{doc.txt}}`

- Encrypt `doc.txt` with only a passphrase (output to `doc.txt.gpg`):

`gpg --symmetric {{doc.txt}}`

- Decrypt `doc.txt.gpg` (output to stdout):

`gpg --decrypt {{doc.txt.gpg}}`

- Import a public key:

`gpg --import {{public.gpg}}`

- Export public key for [alice@example.com](mailto:alice@example.com) (output to stdout):

`gpg --export --armor {{alice@example.com}}`

- Export private key for [alice@example.com](mailto:alice@example.com) (output to stdout):

`gpg --export-secret-keys --armor {{alice@example.com}}`

