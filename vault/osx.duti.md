---
id: osx.duti
title: Duti
desc: ''
updated: 1644840636308
created: 1644840636308
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# duti

> Set default applications for document types and URL schemes on macOS.
> More information: <https://github.com/moretension/duti>.

- Set Safari as the default handler for HTML documents:

`duti -s {{com.apple.Safari}} {{public.html}} all`

- Set VLC as the default viewer for files with `.m4v` extensions:

`duti -s {{org.videolan.vlc}} {{m4v}} viewer`

- Set Finder as the default handler for the ftp:// URL scheme:

`duti -s {{com.apple.Finder}} "{{ftp}}"`

- Display information about the default application for a given extension:

`duti -x {{ext}}`

- Display the default handler for a given UTI:

`duti -d {{uti}}`

- Display all handlers of a given UTI:

`duti -l {{uti}}`

