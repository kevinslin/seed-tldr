---
id: common.josm
title: Josm
desc: ''
updated: 1623965306194
created: 1623965306194
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# josm

> Extensible OpenStreetMap editor for Java 8+.
> More information: <https://josm.openstreetmap.de/>.

- Launch JOSM:

`josm`

- Launch JOSM in maximized mode:

`josm --maximize`

- Launch JOSM and set a specific language:

`josm --language {{de}}`

- Launch JOSM and reset all preferences to their default values:

`josm --reset-preferences`

- Launch JOSM and download a specific bounding box:

`josm --download {{minlat,minlon,maxlat,maxlon}}`

- Launch JOSM and download a specific bounding box as raw GPS:

`josm --downloadgps {{minlat,minlon,maxlat,maxlon}}`

- Launch JOSM without plugins:

`josm --skip-plugins`

