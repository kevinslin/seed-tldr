---
id: common.sn
title: Sn
desc: ''
updated: 1615663978734
created: 1615663978734
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sn

> Mono StrongName utility for signing and verifying IL assemblies.

- Generate a new StrongNaming key:

`sn -k {{path/to/key.snk}}`

- Re-sign an assembly with the specified private key:

`sn -R {{path/to/assembly.dll}} {{path/to/keypair.snk}}`

- Show the public key of the private key that was used to sign an assembly:

`sn -T {{path/to/assembly.exe}}`

- Extract the public key to a file:

`sn -e {{path/to/assembly.dll}} {{path/to/output.pub}}`
