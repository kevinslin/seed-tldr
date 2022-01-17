---
id: common.opusenc
title: Opusenc
desc: ''
updated: 1642441815054
created: 1642441815054
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# opusenc

> Convert WAV or FLAC audio to Opus.
> More information: <https://opus-codec.org/docs/opus-tools/opusenc.html>.

- Convert WAV to Opus using default options:

`opusenc {{path/to/input.wav}} {{path/to/output}}.opus`

- Convert stereo audio at the highest quality level:

`opusenc --bitrate {{512}} {{path/to/input.wav}} {{path/to/output}}.opus`

- Convert 5.1 surround sound audio at the highest quality level:

`opusenc --bitrate {{1536}} {{path/to/input.flac}} {{path/to/output}}.opus`

- Convert speech audio at the lowest quality level:

`opusenc {{path/to/input.wav}} --downmix-mono --bitrate {{6}} {{path/to/out}}.opus`

