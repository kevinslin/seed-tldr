---
id: common.compare
title: Compare
desc: ''
updated: 1615655543048
created: 1615655543048
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# compare

> View the difference between 2 images.
> More information: <https://imagemagick.org/script/compare.php>.

- Compare 2 images:

`compare {{image1.png}} {{image2.png}} {{diff.png}}`

- Compare 2 images using a custom metric:

`compare -verbose -metric {{PSNR}} {{image1.png}} {{image2.png}} {{diff.png}}`

