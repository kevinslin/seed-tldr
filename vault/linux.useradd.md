---
id: linux.useradd
title: Useradd
desc: ''
updated: 1642441815116
created: 1642441815116
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# useradd

> Create a new user.
> More information: <https://manned.org/useradd>.

- Create new user:

`useradd {{name}}`

- Create new user with a default home directory:

`useradd --create-home {{name}}`

- Create new user with specified shell:

`useradd --shell {{path/to/shell}} {{name}}`

- Create new user belonging to additional groups (mind the lack of whitespace):

`useradd --groups {{group1,group2}} {{name}}`

- Create new system user without a home directory:

`useradd --no-create-home --system {{name}}`

