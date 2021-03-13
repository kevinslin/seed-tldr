---
id: common.identify
title: Identify
desc: ''
updated: 1615663978719
created: 1615663978719
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# identify

> Command line utility of Image Magick project to describe the format and characteristics of one or more image files.
> More information: <https://imagemagick.org/script/identify.php>.

- Collect dimensions of all jpeg files under current directory:

`identify -format "%f,%w,%h\n" *.{{jpg}} > {{filelist.csv}}`

