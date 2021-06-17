---
id: linux.fsck
title: Fsck
desc: ''
updated: 1623965306222
created: 1623965306222
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fsck

> Check the integrity of a filesystem or repair it. The filesystem should be unmounted at the time the command is run.

- Check filesystem `/dev/sdX`, reporting any damaged blocks:

`fsck {{/dev/sdX}}`

- Check filesystem `/dev/sdX`, reporting any damaged blocks and interactively letting the user choose to repair each one:

`fsck -r {{/dev/sdX}}`

- Check filesystem `/dev/sdX`, reporting any damaged blocks and automatically repairing them:

`fsck -a {{/dev/sdX}}`

