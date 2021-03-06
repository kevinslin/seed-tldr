---
id: linux.wodim
title: Wodim
desc: ''
updated: 1623965306232
created: 1623965306232
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wodim

> Command (aliased as `cdrecord` on some systems) for recording data to CDs or DVDs.
> Some invocations of wodim can cause destructive actions, such as erasing all the data on a disc.

- Display optical drives available to `wodim`:

`wodim --devices`

- Record ("burn") an audio-only disc:

`wodim dev=/dev/{{optical_drive}} -audio {{track*.cdaudio}}`

- Burn a file to a disc, ejecting the disc once done (some recorders require this):

`wodim -eject dev=/dev/{{optical_drive}} -data {{file.iso}}`

- Burn a file to the disc in an optical drive, potentially writing to multiple discs in succession:

`wodim -tao dev=/dev/{{optical_drive}} -data {{file.iso}}`

