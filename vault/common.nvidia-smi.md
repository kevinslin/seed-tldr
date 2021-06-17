---
id: common.nvidia-smi
title: Nvidia Smi
desc: ''
updated: 1623965016140
created: 1623965016140
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nvidia-smi

> Aid the management and monitoring of NVIDIA GPU devices.
> More information: <https://developer.nvidia.com/nvidia-system-management-interface>.

- Display information on all available GPUs and processes using them:

`nvidia-smi`

- Display more detailed GPU information:

`nvidia-smi --query`

- Monitor overall GPU usage with 1-second update interval:

`nvidia-smi dmon`

