---
id: linux.chfn
title: Chfn
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chfn

> Update `finger` info for a user.
> More information: <https://manned.org/chfn>.

- Update a user's "Name" field in the output of `finger`:

`chfn -f {{new_display_name}} {{username}}`

- Update a user's "Office Room Number" field for the output of `finger`:

`chfn -o {{new_office_room_number}} {{username}}`

- Update a user's "Office Phone Number" field for the output of `finger`:

`chfn -p {{new_office_telephone_number}} {{username}}`

- Update a user's "Home Phone Number" field for the output of `finger`:

`chfn -h {{new_home_telephone_number}} {{username}}`

