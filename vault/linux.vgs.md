---
id: linux.vgs
title: Vgs
desc: ''
updated: 1615655543111
created: 1615655543111
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# vgs

> Display information about volume groups.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/vgs.8.html>.

- Display information about volume groups:

`vgs`

- Display all volume groups:

`vgs -a`

- Change default display to show more details:

`vgs -v`

- Display only specific fields:

`vgs -o {{field_name_1}},{{field_name_2}}`

- Append field to default display:

`vgs -o +{{field_name}}`

- Suppress heading line:

`vgs --noheadings`

- Use separator to separate fields:

`vgs --separator =`

