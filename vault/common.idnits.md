---
id: common.idnits
title: Idnits
desc: ''
updated: 1642441815034
created: 1642441815034
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# idnits

> Check internet-drafts for submission nits.
> Looks for violations of Section 2.1 and 2.2 of the requirements listed on <https://www.ietf.org/id-info/checklist>.
> More information: <https://tools.ietf.org/tools/idnits/>.

- Check a file for nits:

`idnits {{path/to/file.txt}}`

- Count nits without displaying them:

`idnits --nitcount {{path/to/file.txt}}`

- Show extra information about offending lines:

`idnits --verbose {{path/to/file.txt}}`

- Expect the specified year in the boilerplate instead of the current year:

`idnits --year {{2021}} {{path/to/file.txt}}`

- Assume the document is of the specified status:

`idnits --doctype {{standard|informational|experimental|bcp|ps|ds}} {{path/to/file.txt}}`

