---
id: common.mmls
title: Mmls
desc: ''
updated: 1615663978723
created: 1615663978723
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mmls

> Display the partition layout of a volume system.
> More information: <https://wiki.sleuthkit.org/index.php?title=Mmls>.

- Display the partition table stored in an image file:

`mmls {{path/to/image_file}}`

- Display the partition table with an additional column for the partition size:

`mmls -B -i {{path/to/image_file}}`

- Display the partition table in a split EWF image:

`mmls -i ewf {{image.e01}} {{image.e02}}`

- Display nested partition tables:

`mmls -t {{nested_table_type}} -o {{offset}} {{path/to/image_file}}`
