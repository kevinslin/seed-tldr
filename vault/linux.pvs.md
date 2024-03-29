---
id: linux.pvs
title: Pvs
desc: ''
updated: 1642441815109
created: 1642441815109
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pvs

> Display information about physical volumes.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/pvs.8.html>.

- Display information about physical volumes:

`pvs`

- Display non-physical volumes:

`pvs -a`

- Change default display to show more details:

`pvs -v`

- Display only specific fields:

`pvs -o {{field_name_1}},{{field_name_2}}`

- Append field to default display:

`pvs -o +{{field_name}}`

- Suppress heading line:

`pvs --noheadings`

- Use separator to separate fields:

`pvs --separator {{special_character}}`

