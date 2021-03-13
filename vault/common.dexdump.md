---
id: common.dexdump
title: Dexdump
desc: ''
updated: 1615663978705
created: 1615663978705
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dexdump

> Display information about Android DEX files.
> More information: <https://manpages.ubuntu.com/manpages/latest/en/man1/dexdump.1.html>.

- Extract classes and methods from an APK file:

`dexdump {{path/to/file.apk}}`

- Display header information of DEX files contained in an APK file:

`dexdump -f {{path/to/file.apk}}`

- Display the dis-assembled output of executable sections:

`dexdump -d {{path/to/file.apk}}`

- Output results to a file:

`dexdump -o {{path/to/file}} {{path/to/file.apk}}`

