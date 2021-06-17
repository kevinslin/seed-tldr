---
id: common.zipalign
title: Zipalign
desc: ''
updated: 1623965016157
created: 1623965016157
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zipalign

> Zip archive alignment tool.
> Part of the Android SDK build tools.
> More information: <https://developer.android.com/studio/command-line/zipalign>.

- Align the data of a ZIP file on 4-byte boundaries:

`zipalign {{4}} {{path/to/input.zip}} {{path/to/output.zip}}`

- Check that a ZIP file is correctly aligned on 4-byte boundaries and display the results in a verbose manner:

`zipalign -v -c {{4}} {{path/to/input.zip}}`

