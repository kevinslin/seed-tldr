---
id: common.ogrinfo
title: Ogrinfo
desc: ''
updated: 1645970511529
created: 1645970511529
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ogrinfo

> List information about an OGR-supported data source.
> More information: <https://gdal.org/programs/ogrinfo.html>.

- List supported formats:

`ogrinfo --formats`

- List layers of a data source:

`ogrinfo {{path/to/input.gpkg}}`

- Get detailed information about a specific layer of a data source:

`ogrinfo {{path/to/input.gpkg}} {{layer_name}}`

- Only show summary information about a specific layer of a data source:

`ogrinfo -so {{path/to/input.gpkg}} {{layer_name}}`

