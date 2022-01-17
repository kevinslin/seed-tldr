---
id: common.u3d
title: U3d
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# u3d

> Set of tools to interact with Unity from command line.
> More information: <https://github.com/DragonBox/u3d>.

- Open project from the current directory in correct Unity version:

`u3d`

- List installed versions of Unity:

`u3d list`

- List available versions of Unity that can be downloaded:

`u3d available`

- Download and install latest stable Unity version:

`u3d install latest_stable`

- Download and install Unity version and editor [p]ackages:

`u3d install {{2021.2.0f1}} -p {{Unity,iOS,Android}}`

