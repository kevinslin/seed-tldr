---
id: common.compare
title: Compare
desc: ''
updated: 1642441815003
created: 1642441815003
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# compare

> View the difference between 2 images.
> More information: <https://imagemagick.org/script/compare.php>.

- Compare 2 images:

`compare {{image1.png}} {{image2.png}} {{diff.png}}`

- Compare 2 images using a custom metric:

`compare -verbose -metric {{PSNR}} {{image1.png}} {{image2.png}} {{diff.png}}`

