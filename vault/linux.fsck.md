---
id: linux.fsck
title: Fsck
desc: ''
updated: 1642441815095
created: 1642441815095
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fsck

> Check the integrity of a filesystem or repair it. The filesystem should be unmounted at the time the command is run.
> More information: <https://manned.org/fsck>.

- Check filesystem `/dev/sdXN`, reporting any damaged blocks:

`sudo fsck {{/dev/sdXN}}`

- Check filesystem `/dev/sdXN`, reporting any damaged blocks and interactively letting the user choose to repair each one:

`sudo fsck -r {{/dev/sdXN}}`

- Check filesystem `/dev/sdXN`, reporting any damaged blocks and automatically repairing them:

`sudo fsck -a {{/dev/sdXN}}`

