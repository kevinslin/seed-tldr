---
id: common.mogrify
title: Mogrify
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
# mogrify

> Perform operations on multiple images, such as resizing, cropping, flipping, and adding effects.
> Changes are applied directly to the original file.
> More information: <https://imagemagick.org/script/mogrify.php>.

- Resize all JPEG images in the directory to 50% of their initial size:

`mogrify -resize {{50%}} {{*.jpg}}`

- Resize all images starting with "DSC" to 800x600:

`mogrify -resize {{800x600}} {{DSC*}}`

- Convert all PNGs in the directory to JPEG:

`mogrify -format {{jpg}} {{*.png}}`

- Halve the saturation of all image files in the current directory:

`mogrify -modulate {{100,50}} {{*}}`

- Double the brightness of all image files in the current directory:

`mogrify -modulate {{200}} {{*}}`

