---
id: common.identify
title: Identify
desc: ''
updated: 1615655543064
created: 1615655543064
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# identify

> Command line utility of Image Magick project to describe the format and characteristics of one or more image files.
> More information: <https://imagemagick.org/script/identify.php>.

- Collect dimensions of all jpeg files under current directory:

`identify -format "%f,%w,%h\n" *.{{jpg}} > {{filelist.csv}}`

