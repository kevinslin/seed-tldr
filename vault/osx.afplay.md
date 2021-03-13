---
id: osx.afplay
title: Afplay
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# afplay

> Command-line audio player.

- Play a sound file (waits until playback ends):

`afplay {{path/to/file}}`

- Play a sound file at 2x speed (playback rate):

`afplay --rate {{2}} {{path/to/file}}`

- Play a sound file at half speed:

`afplay --rate {{0.5}} {{path/to/file}}`

- Play the first N seconds of a sound file:

`afplay --time {{seconds}} {{path/to/file}}`

