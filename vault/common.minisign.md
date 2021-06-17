---
id: common.minisign
title: Minisign
desc: ''
updated: 1623965306196
created: 1623965306196
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# minisign

> A dead simple tool to sign files and verify signatures.
> More information: <https://jedisct1.github.io/minisign/>.

- Generate a new keypair at the default location:

`minisign -G`

- Sign a file:

`minisign -Sm {{path/to/file}}`

- Sign a file, adding a trusted (signed) and an untrusted (unsigned) comment in the signature:

`minisign -Sm {{path/to/file}} -c "{{Untrusted comment}}" -t "{{Trusted comment}}"`

- Verify a file and the trusted comments in its signature using the specified public key file:

`minisign -Vm {{path/to/file}} -p {{path/to/publickey.pub}}`

- Verify a file and the trusted comments in its signature, specifying a public key as a Base64 encoded literal:

`minisign -Vm {{path/to/file}} -P "{{public_key_base64}}"`

