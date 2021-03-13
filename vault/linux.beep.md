---
id: linux.beep
title: Beep
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# beep

> A utility to beep the PC speaker.

- Play a beep:

`beep`

- Play a beep that repeats:

`beep -r {{repetitions}}`

- Play a beep at a specified frequency (Hz) and duration (milliseconds):

`beep -f {{frequency}} -l {{duration}}`

- Play each new frequency and duration as a distinct beep:

`beep -f {{frequency}} -l {{duration}} -n -f {{frequency}} -l {{duration}}`

- Play the C major scale:

`beep -f 262 -n -f 294 -n -f 330 -n -f 349 -n -f 392 -n -f 440 -n -f 494 -n -f 523`

