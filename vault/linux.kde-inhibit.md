---
id: linux.kde-inhibit
title: Kde Inhibit
desc: ''
updated: 1615663978748
created: 1615663978748
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kde-inhibit

> Inhibit various desktop functions while a command runs.

- Inhibit power management:

`kde-inhibit --power {{command}} {{command_arguments}}`

- Inhibit screen saver:

`kde-inhibit --screenSaver {{command}} {{command_arguments}}`

- Launch vlc, and inhibit colour correction (night mode) while it's running:

`kde-inhibit --colorCorrect {{vlc}}`

