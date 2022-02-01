---
id: linux.findfs
title: Findfs
desc: ''
updated: 1642441815094
created: 1642441815094
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# findfs

> Finds a filesystem by label or UUID.
> More information: <https://mirrors.edge.kernel.org/pub/linux/utils/util-linux>.

- Search block devices by filesystem label:

`findfs LABEL={{label}}`

- Search by filesystem UUID:

`findfs UUID={{uuid}}`

- Search by partition label (GPT or MAC partition table):

`findfs PARTLABEL={{partition_label}}`

- Search by partition UUID (GPT partition table only):

`findfs PARTUUID={{partition_uuid}}`

