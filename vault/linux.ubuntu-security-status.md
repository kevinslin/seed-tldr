---
id: linux.ubuntu-security-status
title: Ubuntu Security Status
desc: ''
updated: 1643509837382
created: 1643509837382
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ubuntu-security-status

> Display information about security support for installed Ubuntu packages.
> More information: <https://git.launchpad.net/ubuntu/+source/update-manager/tree/ubuntu-security-status>.

- Display the number of unsupported packages:

`ubuntu-security-status`

- List packages that are no longer available for download:

`ubuntu-security-status --unavailable`

- List third-party packages:

`ubuntu-security-status --thirdparty`

