---
id: linux.beep
title: Beep
desc: ''
updated: 1642441815088
created: 1642441815088
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# beep

> A utility to beep the PC speaker.
> More information: <https://github.com/spkr-beep/beep>.

- Play a beep:

`beep`

- Play a beep that repeats:

`beep -r {{repetitions}}`

- Play a beep at a specified frequency (Hz) and duration (milliseconds):

`beep -f {{frequency}} -l {{duration}}`

- Play each new frequency and duration as a distinct beep:

`beep -f {{frequency}} -l {{duration}} -n -f {{frequency}} -l {{duration}}`

- Play the C major scale:

`beep -f {{262}} -n -f {{294}} -n -f {{330}} -n -f {{349}} -n -f {{392}} -n -f {{440}} -n -f {{494}} -n -f {{523}}`

