---
id: osx.osascript
title: Osascript
desc: ''
updated: 1623965016174
created: 1623965016174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# osascript

> Run AppleScript or JavaScript for Automation (JXA) from the command-line.

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

