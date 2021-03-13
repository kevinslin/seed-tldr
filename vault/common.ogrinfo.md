---
id: common.ogrinfo
title: Ogrinfo
desc: ''
updated: 1615655543076
created: 1615655543076
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

