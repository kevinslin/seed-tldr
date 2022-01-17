---
id: linux.isoinfo
title: Isoinfo
desc: ''
updated: 1642441815100
created: 1642441815100
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# isoinfo

> Utility programs for dumping and verifying ISO disk images.
> More information: <https://manned.org/isoinfo>.

- List all the files included in an ISO image:

`isoinfo -f -i {{path/to/image.iso}}`

- E[x]tract a specific file from an ISO image and send it out stdout:

`isoinfo -i {{path/to/image.iso}} -x {{/PATH/TO/FILE/INSIDE/ISO.EXT}}`

- Show header information for an ISO disk image:

`isoinfo -d -i {{path/to/image.iso}}`

