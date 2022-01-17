---
id: common.montage
title: Montage
desc: ''
updated: 1642441815048
created: 1642441815048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# montage

> ImageMagick image montage tool.
> Tiles images into a customisable grid.
> More information: <https://imagemagick.org/script/montage.php>.

- Tile images into a grid, automatically resizing images larger than the grid cell size:

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} montage.jpg`

- Tile images into a grid, automatically calculating the grid cell size from the largest image:

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} -geometry +0+0 montage.jpg`

- Set the grid cell size and resize images to fit it before tiling:

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} -geometry 640x480+0+0 montage.jpg`

- Limit the number of rows and columns in the grid, causing input images to overflow into multiple output montages:

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} -geometry +0+0 -tile 2x3 montage_%d.jpg`

- Resize and crop images to fill their grid cells before tiling:

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} -geometry +0+0 -resize 640x480^ -gravity center -crop 640x480+0+0 montage.jpg`

