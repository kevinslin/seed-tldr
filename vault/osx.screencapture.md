---
id: osx.screencapture
title: Screencapture
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# screencapture

> Utility to take screenshots and screen recordings.

- Take a screenshot and save it to a file:

`screencapture {{path/to/file.png}}`

- Take a screenshot including the mouse cursor:

`screencapture -C {{path/to/file.png}}`

- Take a screenshot and open it in Preview, instead of saving:

`screencapture -P`

- Take a screenshot of a selected rectangular area:

`screencapture -i {{path/to/file.png}}`

- Take a screenshot after a delay:

`screencapture -T {{seconds}} {{path/to/file.png}}`

- Make a screen recording and save it to a file:

`screencapture -v {{path/to/file.mp4}}`

