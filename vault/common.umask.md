---
id: common.umask
title: Umask
desc: ''
updated: 1623965306214
created: 1623965306214
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# umask

> Manage the read/write/execute permissions that are masked out (i.e. restricted) for newly created files by the user.

- Display the current mask in octal notation:

`umask`

- Display the current mask in symbolic (human-readable) mode:

`umask -S`

- Change the mask symbolically to allow read permission for all users (the rest of the mask bits are unchanged):

`umask {{a+r}}`

- Set the mask (using octal) to restrict no permissions for the file's owner, and restrict all permissions for everyone else:

`umask {{077}}`

