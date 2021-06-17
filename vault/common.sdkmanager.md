---
id: common.sdkmanager
title: Sdkmanager
desc: ''
updated: 1623965306209
created: 1623965306209
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sdkmanager

> Tool to install packages for the Android SDK.
> More information: <https://developer.android.com/studio/command-line/sdkmanager>.

- List available packages:

`sdkmanager --list`

- Install a package:

`sdkmanager {{package}}`

- Update every installed package:

`sdkmanager --update`

- Uninstall a package:

`sdkmanager --uninstall {{package}}`

