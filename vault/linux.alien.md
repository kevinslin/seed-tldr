---
id: linux.alien
title: Alien
desc: ''
updated: 1642441815087
created: 1642441815087
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# alien

> Convert different installation packages to other formats.
> More information: <https://manned.org/alien>.

- Convert a specific installation file to Debian format (`.deb` extension):

`sudo alien --to-deb {{path/to/file}}`

- Convert a specific installation file to Red Hat format (`.rpm` extension):

`sudo alien --to-rpm {{path/to/file}}`

- Convert a specific installation file to a Slackware installation file (`.tgz` extension):

`sudo alien --to-tgz {{path/to/file}}`

- Convert a specific installation file to Debian format and install on the system:

`sudo alien --to-deb --install {{path/to/file}}`

