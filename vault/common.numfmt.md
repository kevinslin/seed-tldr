---
id: common.numfmt
title: Numfmt
desc: ''
updated: 1623965306201
created: 1623965306201
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# numfmt

> Convert numbers to and from human-readable strings.
> More information: <https://www.gnu.org/software/coreutils/numfmt>.

- Convert 1.5K (SI Units) to 1500:

`numfmt --from={{si}} {{1.5K}}`

- Convert 5th field (1-indexed) to IEC Units without converting header:

`ls -l | numfmt --header={{1}} --field={{5}} --to={{iec}}`

- Convert to IEC units, pad with 5 characters, left aligned:

`du -s * | numfmt --to={{iec}} --format="{{%-5f}}"`

