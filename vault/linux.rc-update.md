---
id: linux.rc-update
title: Rc Update
desc: ''
updated: 1643286593627
created: 1643286593627
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rc-update

> Add and remove OpenRC services to and from runlevels.
> See also `openrc`.
> More information: <https://manned.org/rc-update>.

- List all services and the runlevels they are added to:

`rc-update show`

- Add a service to a runlevel:

`sudo rc-update add {{service_name}} {{runlevel}}`

- Delete a service from a runlevel:

`sudo rc-update delete {{service_name}} {{runlevel}}`

- Delete a service from all runlevels:

`sudo rc-update --all delete {{service_name}}`

