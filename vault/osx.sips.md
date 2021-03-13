---
id: osx.sips
title: Sips
desc: ''
updated: 1615663978761
created: 1615663978761
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sips

> Apple Scriptable Image Processing System.
> Raster/Query images and ColorSync ICC Profiles.

- Specify an output directory so that originals do not get modified:

`sips --out {{path/to/out_dir}}`

- Resample image at specified size, Image aspect ratio may be altered:

`sips -z {{1920}} {{300}} {{image.ext}}`

- Resample image so height and width aren't greater than specified size (notice the capital Z):

`sips -Z {{1920}} {{300}} {{image.ext}}`

- Resample all images in a directory to fit a width of 960px (honoring aspect ratio):

`sips --resampleWidth {{960}} {{path/to/images}}`

- Convert an image from CMYK to RGB:

`sips --matchTo '/System/Library/ColorSync/Profiles/Generic RGB Profile.icc' {{path/to/image.ext}} {{path/to/out_dir}}`

- Remove ColorSync ICC profile from an image:

`sips -d profile --deleteColorManagementProperties {{path/to/image.ext}}`
