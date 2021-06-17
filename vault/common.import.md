---
id: common.import
title: Import
desc: ''
updated: 1623965016132
created: 1623965016132
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# import

> Capture some or all of an X server screen, and save the image to a file.
> Part of the ImageMagick library.

- Capture the entire X server screen in the PostScript image format:

`import -window root {{output.postscript}}`

- Capture contents of a remote X server screen in the PNG image format:

`import -window root -display {{remote_host}}:{screen}.{display} {{output.png}}`

- Capture a specific window, given its ID as displayed by `xwininfo`, into the JPEG format:

`import -window {{window_id}} {{output.jpg}}`

