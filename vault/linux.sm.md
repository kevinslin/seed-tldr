---
id: linux.sm
title: Sm
desc: ''
updated: 1642441815113
created: 1642441815113
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sm

> Displays a short message fullscreen.
> More information: <https://github.com/nomeata/screen-message>.

- Display a message in full-screen:

`sm "{{Hello World!}}"`

- Display a message with inverted colors:

`sm -i "{{Hello World!}}"`

- Display a message with a custom foreground color:

`sm -f {{blue}} "{{Hello World!}}"`

- Display a message with a custom background color:

`sm -b {{#008888}} "{{Hello World!}}"`

- Display a message rotated 3 times (in steps of 90 degrees, counterclockwise):

`sm -r {{3}} "{{Hello World!}}"`

- Display a message using the output from another command:

`{{echo "Hello World!"}} | sm -`

