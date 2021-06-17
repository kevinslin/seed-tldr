---
id: common.gdalbuildvrt
title: Gdalbuildvrt
desc: ''
updated: 1623965306185
created: 1623965306185
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdalbuildvrt

> Build Virtual Datasets from a list of existing datasets.
> More information: <https://gdal.org/programs/gdalbuildvrt.html>.

- Make a virtual mosaic from all TIFF files contained in a directory:

`gdalbuildvrt {{path/to/output.vrt}} {{path/to/input_directory/*.tif}}`

- Make a virtual mosaic from files whose name is specified in a text file:

`gdalbuildvrt -input_file_list {{path/to/list.txt}} {{path/to/output.vrt}}`

- Make a RGB virtual mosaic from 3 single-band input files:

`gdalbuildvrt -separate {{path/to/rgb.vrt}} {{path/to/red.tif}} {{path/to/green.tif}} {{path/to/blue.tif}}`

- Make a virtual mosaic with blue background colour (RGB: 0 0 255):

`gdalbuildvrt -hidenodata -vrtnodata "{{0 0 255}}" {{path/to/output.vrt}} {{path/to/input_directory/*.tif}}`

