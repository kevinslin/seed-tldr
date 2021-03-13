---
id: common.zopflipng
title: Zopflipng
desc: ''
updated: 1615655543094
created: 1615655543094
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# zopflipng

> PNG image compression utility.
> More information: <https://github.com/google/zopfli>.

- Optimize a PNG image:

`zopflipng {{input.png}} {{output.png}}`

- Optimize several PNG images and save with given prefix:

`zopflipng --prefix={{prefix}} {{image1.png}} {{image2.png}} {{image3.png}}`

