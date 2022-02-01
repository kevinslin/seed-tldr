---
id: linux.pw-record
title: Pw Record
desc: ''
updated: 1642441815109
created: 1642441815109
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pw-record

> Shorthand tool for pw-cat --playback.
> More information: <https://fedoraproject.org/wiki/QA:Testcase_PipeWire_PipeWire_CLI>.

- List all available record targets:

`pw-record --list-targets`

- Record a sample recording using the default target:

`pw-record {{path/to/file.wav}}`

- Record a sample recording at a different volume level:

`pw-record --volume={{0.1}} {{path/to/file.wav}}`

- Record a sample recording using a different sample rate:

`pw-record --rate={{6000}} {{path/to/file.wav}}`

