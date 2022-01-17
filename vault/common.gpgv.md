---
id: common.gpgv
title: Gpgv
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
# gpgv

> Verify OpenPGP signatures.
> More information: <https://www.gnupg.org/documentation/manuals/gnupg/gpgv.html>.

- Verify a signed file:

`gpgv {{path/to/file}}`

- Verify a signed file using a detached signature:

`gpgv {{path/to/signature}} {{path/to/file}}`

- Add a file to the list of keyrings (a single exported key also counts as a keyring):

`gpgv --keyring {{./alice.keyring}} {{path/to/signature}} {{path/to/file}}`

