---
id: linux.do-release-upgrade
title: Do Release Upgrade
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# do-release-upgrade

> The Ubuntu release upgrader.
> More information: <https://ubuntu.com/server/docs/upgrade-introduction>.

- Upgrade to the latest release:

`sudo do-release-upgrade`

- Upgrade to the latest development release:

`sudo do-release-upgrade --devel-release`

- Upgrade to the latest proposed release:

`sudo do-release-upgrade --proposed`

