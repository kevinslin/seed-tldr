---
id: linux.mt
title: Mt
desc: ''
updated: 1642441815104
created: 1642441815104
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mt

> Control magnetic tape drive operation (commonly LTO tape).
> More information: <https://manned.org/mt>.

- Check the status of a tape drive:

`mt -f {{/dev/nstX}} status`

- Rewind the tape to beginning:

`mt -f {{/dev/nstX}} rewind`

- Move forward a given files, then position the tape on first block of next file:

`mt -f {{/dev/nstX}} fsf {{count}}`

- Rewind the tape, then position the tape at beginning of the given file:

`mt -f {{/dev/nstX}} asf {{count}}`

- Position the tape at the end of valid data:

`mt -f {{/dev/nstX}} eod`

- Rewind the tape and unload/eject it:

`mt -f {{/dev/nstX}} eject`

- Write EOF (End-of-file) mark at the current position:

`mt -f {{/dev/nstX} eof`

