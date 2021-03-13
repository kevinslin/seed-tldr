---
id: linux.fsck
title: Fsck
desc: ''
updated: 1615655543101
created: 1615655543101
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# fsck

> Check the integrity of a filesystem or repair it. The filesystem should be unmounted at the time the command is run.

- Check filesystem `/dev/sdX`, reporting any damaged blocks:

`fsck {{/dev/sdX}}`

- Check filesystem `/dev/sdX`, reporting any damaged blocks and interactively letting the user choose to repair each one:

`fsck -r {{/dev/sdX}}`

- Check filesystem `/dev/sdX`, reporting any damaged blocks and automatically repairing them:

`fsck -a {{/dev/sdX}}`

