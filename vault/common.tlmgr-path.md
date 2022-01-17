---
id: common.tlmgr-path
title: Tlmgr Path
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tlmgr path

> Add or remove symlinks for TeX Live executables, man pages and info pages.
> This command has to be re-run for files added in the future.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Add symlinks to TeX Live files:

`sudo tlmgr path add`

- Remove symlinks to TeX Live files:

`sudo tlmgr path remove`

