---
id: common.dive
title: Dive
desc: ''
updated: 1615655543051
created: 1615655543051
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# dive

> A tool for exploring a Docker image, layer contents, and discovering ways to shrink it.
> More information: <https://github.com/wagoodman/dive>.

- Analyze a Docker image:

`dive {{your_image_tag}}`

- Build an image and start analyzing it:

`dive build -t {{some_tag}}`

