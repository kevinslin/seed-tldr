---
id: linux.slop
title: Slop
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# slop

> Get a selection of the screen.
> More information: <https://github.com/naelstrof/slop>.

- Wait for the user to make a selection and output its geometry to standard output:

`slop`

- Double click, rather than click and drag, to draw a selection:

`slop -D`

- Highlight the selection rather than outlining it:

`slop -l`

- Specify the output format:

`slop -f {{format_string}}`

- Specify the selection rectangle's color:

`slop -c {{red}},{{green}},{{blue}},{{alpha}}`

