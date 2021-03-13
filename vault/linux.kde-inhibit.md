---
id: linux.kde-inhibit
title: Kde Inhibit
desc: ''
updated: 1615655543103
created: 1615655543103
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# kde-inhibit

> Inhibit various desktop functions while a command runs.

- Inhibit power management:

`kde-inhibit --power {{command}} {{command_arguments}}`

- Inhibit screen saver:

`kde-inhibit --screenSaver {{command}} {{command_arguments}}`

- Launch vlc, and inhibit colour correction (night mode) while it's running:

`kde-inhibit --colorCorrect {{vlc}}`

