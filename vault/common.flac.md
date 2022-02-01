---
id: common.flac
title: Flac
desc: ''
updated: 1642441815018
created: 1642441815018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# flac

> Encodes, decodes and tests FLAC files.
> More information: <https://xiph.org/flac>.

- Encode a WAV file to FLAC (this will create a FLAC file in the same location as the WAV file):

`flac {{path/to/file.wav}}`

- Encode a WAV file to FLAC, specifying the output file:

`flac -o {{path/to/output.flac}} {{path/to/file.wav}}`

- Decode a FLAC file to WAV, specifying the output file:

`flac -d -o {{path/to/output.wav}} {{path/to/file.flac}}`

- Test a FLAC file for the correct encoding:

`flac -t {{path/to/file.flac}}`

