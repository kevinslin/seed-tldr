---
id: common.aapt
title: Aapt
desc: ''
updated: 1615655543042
created: 1615655543042
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# aapt

> Android Asset Packaging Tool.
> Compile and package an Android app's resources.
> More information: <https://elinux.org/Android_aapt>.

- List files contained in an APK archive:

`aapt list {{path/to/app.apk}}`

- Display an app's metadata (version, permissions, etc.):

`aapt dump badging {{path/to/app.apk}}`

- Create a new APK archive with files from the specified directory:

`aapt package -F {{path/to/app.apk}} {{path/to/directory}}`

