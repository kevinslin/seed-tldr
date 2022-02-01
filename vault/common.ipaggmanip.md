---
id: common.ipaggmanip
title: Ipaggmanip
desc: ''
updated: 1642441815036
created: 1642441815036
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipaggmanip

> Manipulate aggregate statistics produced by `ipaggcreate`.
> More information: <https://manned.org/ipaggmanip>.

- Combine labels equal in their high-order bits:

`ipaggmanip --prefix {{16}} {{path/to/file}}`

- Remove labels with a count smaller than a given number of bytes and output a random sample of such labels:

`ipaggmanip --cut-smaller {{100}} --cull-labels {{5}} {{path/to/file}}`

- Replace each label's count with 1 if it is non-zero:

`ipaggmanip --posterize {{path/to/file}}`

