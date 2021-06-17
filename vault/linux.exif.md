---
id: linux.exif
title: Exif
desc: ''
updated: 1623965016161
created: 1623965016161
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# exif

> Show and change EXIF information in JPEG files.
> More information: <https://github.com/libexif/exif/>.

- Show all recognized EXIF information in an image:

`exif {{path/to/image.jpg}}`

- Show a table listing known EXIF tags and whether each one exists in an image:

`exif --list-tags --no-fixup {{image.jpg}}`

- Extract the image thumbnail into the file `thumbnail.jpg`:

`exif --extract-thumbnail --output={{thumbnail.jpg}} {{image.jpg}}`

- Show the raw contents of the "Model" tag in the given image:

`exif --ifd={{0}} --tag={{Model}} --machine-readable {{image.jpg}}`

- Change the value of the "Artist" tag to John Smith and save to `new.jpg`:

`exif --output={{new.jpg}} --ifd={{0}} --tag="{{Artist}}" --set-value="{{John Smith}}" --no-fixup {{image.jpg}}`

