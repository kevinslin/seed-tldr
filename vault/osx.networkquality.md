---
id: osx.networkquality
title: Networkquality
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# networkQuality

> Measure the network quality by connecting to the internet.
> More information: <https://support.apple.com/HT212313>.

- Test the network quality for the default interface:

`networkQuality`

- Test the upload and download speeds sequentially instead of in parallel:

`networkQuality -s`

- Test a specified network interface:

`networkQuality -I {{en0}}`

- Test the network quality with verbose output:

`networkQuality -v`

