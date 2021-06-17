---
id: android.am
title: Am
desc: ''
updated: 1623965016110
created: 1623965016110
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# am

> Android activity manager.
> More information: <https://developer.android.com/studio/command-line/adb#am>.

- Start a specific activity:

`am start -n {{com.android.settings/.Settings}}`

- Start an activity and pass data to it:

`am start -a {{android.intent.action.VIEW}} -d {{tel:123}}`

- Start an activity matching a specific action and category:

`am start -a {{android.intent.action.MAIN}} -c {{android.intent.category.HOME}}`

- Convert an intent to an URI:

`am to-uri -a {{android.intent.action.VIEW}} -d {{tel:123}}`

