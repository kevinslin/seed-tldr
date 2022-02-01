---
id: common.timidity
title: Timidity
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# timidity

> TiMidity++ is a MIDI file player and convertor.
> More information: <http://timidity.sourceforge.net>.

- Play a MIDI file:

`timidity {{path/to/file.mid}}`

- Play a MIDI file in a loop:

`timidity --loop {{path/to/file.mid}}`

- Play a MIDI file in a specific key (0 = C major/A minor, -1 = F major/D minor, +1 = G major/E minor, etc.):

`timidity --force-keysig={{-flats|+sharps}} {{path/to/file.mid}}`

- Convert a MIDI file to PCM (WAV) audio:

`timidity --output-mode={{w}} --output-file={{path/to/file.wav}} {{path/to/file.mid}}`

- Convert a MIDI file to FLAC audio:

`timidity --output-mode={{F}} --output-file={{path/to/file.flac}} {{path/to/file.mid}}`

