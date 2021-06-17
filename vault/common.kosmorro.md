---
id: common.kosmorro
title: Kosmorro
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
# kosmorro

> Compute the ephemerides and the events for a given date, at a given position on Earth.
> More information: <http://kosmorro.space>.

- Get ephemerides for Paris, France:

`kosmorro --latitude={{48.7996}} --longitude={{2.3511}}`

- Get ephemerides for Paris, France, in the UTC+2 timezone:

`kosmorro --latitude={{48.7996}} --longitude={{2.3511}} --timezone={{2}}`

- Get ephemerides for Paris, France, on June 9th, 2020:

`kosmorro --latitude={{48.7996}} --longitude={{2.3511}} --date={{2020-06-09}}`

- Generate a PDF (note: TeXLive must be installed):

`kosmorro --format={{pdf}} --output={{path/to/file.pdf}}`

