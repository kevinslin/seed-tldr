---
id: linux.pw-cat
title: Pw Cat
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
# pw-cat

> Pipewire tool for playing and recording audio files.
> More information: <https://fedoraproject.org/wiki/QA:Testcase_PipeWire_PipeWire_CLI>.

- List all available playback targets:

`pw-cat --playback --list-targets`

- Play a WAV file over the default target:

`pw-cat --playback {{path/to/file.wav}}`

- List all available record targets:

`pw-cat --record --list-targets`

- Record a sample recording at a different volume level:

`pw-cat --record --volume={{0.1}} {{path/to/file.wav}}`

- Record a sample recording using a different sample rate:

`pw-cat --record --rate={{6000}} {{path/to/file.wav}}`

