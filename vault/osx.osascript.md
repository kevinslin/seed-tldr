---
id: osx.osascript
title: Osascript
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# osascript

> Run AppleScript or JavaScript for Automation (JXA) from the command line.

- Run an AppleScript command:

`osascript -e '{{say "Hello world"}}'`

- Run multiple AppleScript commands:

`osascript -e '{{say "Hello"}}' -e '{{say "world"}}'`

- Run a compiled (`*.scpt`), bundled (`*.scptd`), or plaintext (`*.applescript`) AppleScript file:

`osascript {{path/to/apple.scpt}}`

- Get the bundle identifier of an application (useful for `open -b`):

`osascript -e 'id of app "{{Application}}"'`

- Run a JavaScript command:

`osascript -l JavaScript -e '{{console.log("Hello world");}}'`

- Run a JavaScript file:

`osascript -l JavaScript {{path/to/script.js}}`

