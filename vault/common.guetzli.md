---
id: common.guetzli
title: Guetzli
desc: ''
updated: 1615655543061
created: 1615655543061
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# guetzli

> JPEG image compression utility.
> More information: <https://github.com/google/guetzli>.

- Compress a JPEG image:

`guetzli {{input.jpg}} {{output.jpg}}`

- Create compressed JPEG image from PNG image:

`guetzli {{input.png}} {{output.jpg}}`

- Compress a JPEG image with desired visual quality (84-100):

`guetzli --quality {{quality_value}} {{input.jpg}} {{output.jpg}}`

