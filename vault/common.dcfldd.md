---
id: common.dcfldd
title: Dcfldd
desc: ''
updated: 1642441815007
created: 1642441815007
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dcfldd

> Enhanced version of dd for forensics and security.
> More information: <http://dcfldd.sourceforge.net/>.

- Copy a disk to a raw image file and hash the image using SHA256:

`dcfldd if=/dev/{{disk_device}} of={{file.img}} hash=sha256 hashlog={{file.hash}}`

- Copy a disk to a raw image file, hashing each 1 GB chunk:

`dcfldd if=/dev/{{disk_device}} of={{file.img}} hash={{sha512|sha384|sha256|sha1|md5}} hashlog={{file.hash}} hashwindow={{1G}}`

