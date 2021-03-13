---
id: common.opusenc
title: Opusenc
desc: ''
updated: 1615655543076
created: 1615655543076
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

