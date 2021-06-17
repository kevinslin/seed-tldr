---
id: common.ogrinfo
title: Ogrinfo
desc: ''
updated: 1623965016141
created: 1623965016141
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

- List layers of a GeoPackage:

`ogrinfo {{input}}.gpkg`

- Get detailed information about a specific layer of a GeoPackage:

`ogrinfo {{input}}.gpkg {{layer_name}}`

- Only show summary information about a specific layer of a GeoPackage:

`ogrinfo -so {{input}}.gpkg {{layer_name}}`

