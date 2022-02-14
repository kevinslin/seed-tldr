---
id: osx.fdesetup
title: Fdesetup
desc: ''
updated: 1644840636308
created: 1644840636308
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fdesetup

> Set and retrieve FileVault related information.
> More information: <https://www.unix.com/man-page/mojave/8/fdesetup/>.

- List current FileVault enabled users:

`sudo fdesetup list`

- Get current FileVault status:

`fdesetup status`

- Add FileVault enabled user:

`sudo fdesetup add -usertoadd user1`

- Enable FileVault:

`sudo fdesetup enable`

- Disable FileVault:

`sudo fdesetup disable`

