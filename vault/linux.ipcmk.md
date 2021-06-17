---
id: linux.ipcmk
title: Ipcmk
desc: ''
updated: 1623965306224
created: 1623965306224
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipcmk

> Create IPC (Inter-process Communication) resources.

- Create a shared memory segment:

`ipcmk --shmem {{segment_size_in_bytes}}`

- Create a semaphore:

`ipcmk --semaphore {{element_size}}`

- Create a message queue:

`ipcmk --queue`

- Create a shared memory segment with specific permissions (default is 0644):

`ipcmk --shmem {{segment_size_in_bytes}} {{octal_permissons}}`

