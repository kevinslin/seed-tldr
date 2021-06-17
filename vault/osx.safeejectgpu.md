---
id: osx.safeejectgpu
title: Safeejectgpu
desc: ''
updated: 1623965016174
created: 1623965016174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# SafeEjectGPU

> Eject a GPU safely.
> Visit the man page for more info.

- Eject all GPUs:

`SafeEjectGPU Eject`

- List all GPUs attached:

`SafeEjectGPU gpus`

- List apps using a GPU:

`SafeEjectGPU gpuid {{GPU_ID}} apps`

- Get the status of a GPU:

`SafeEjectGPU gpuid {{GPU_ID}} status`

- Eject a GPU:

`SafeEjectGPU gpuid {{GPU_ID}} Eject`

- Launch an app on a GPU:

`SafeEjectGPU gpuid {{GPU_ID}} LaunchOnGPU {{path/to/App.app}}`

