---
id: common.numfmt
title: Numfmt
desc: ''
updated: 1615655543075
created: 1615655543075
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# numfmt

> Convert numbers to and from human-readable strings.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/numfmt-invocation.html>.

- Convert 1.5K (SI Units) to 1500:

`numfmt --from={{si}} {{1.5K}}`

- Convert 5th field (1-indexed) to IEC Units without converting header:

`ls -l | numfmt --header={{1}} --field={{5}} --to={{iec}}`

- Convert to IEC units, pad with 5 characters, left aligned:

`du -s * | numfmt --to={{iec}} --format="{{%-5f}}"`

