---
id: osx.bless
title: Bless
desc: ''
updated: 1623965306233
created: 1623965306233
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bless

> Set volume boot capability and startup disk options.
> More information: <https://ss64.com/osx/bless.html>.

- Bless a volume with only Mac OS X or Darwin, and create the BootX and `boot.efi` files as needed:

`bless --folder "{{/Volumes/Mac OS X/System/Library/CoreServices}}" --bootinfo --bootefi`

- Set a volume containing either Mac OS 9 and Mac OS X to be the active volume:

`bless --mount "{{/Volumes/Mac OS}}" --setBoot`

- Set the system to NetBoot and broadcast for an available server:

`bless --netboot --server {{bsdp://255.255.255.255}}`

- Gather information about the currently selected volume (as determined by the firmware), suitable for piping to a program capable of parsing Property Lists:

`bless --info --plist`

