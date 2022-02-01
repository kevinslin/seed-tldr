---
id: linux.lynis
title: Lynis
desc: ''
updated: 1642441815103
created: 1642441815103
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lynis

> System and security auditing tool.
> More information: <https://cisofy.com/documentation/lynis/>.

- Check that Lynis is up-to-date:

`sudo lynis update info`

- Run a security audit of the system:

`sudo lynis audit system`

- Run a security audit of a Dockerfile:

`sudo lynis audit dockerfile {{path/to/dockerfile}}`

