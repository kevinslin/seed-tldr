---
id: common.adb-shell
title: Adb Shell
desc: ''
updated: 1615655543042
created: 1615655543042
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# adb shell

> Android Debug Bridge Shell: Run remote shell commands on an Android emulator instance or connected Android devices.
> More information: <https://developer.android.com/studio/command-line/adb>.

- Start a remote interactive shell on the emulator/device:

`adb shell`

- Get all the properties from emulator or device:

`adb shell getprop`

- Revert all runtime permissions to their default:

`adb shell pm reset-permissions`

- Revoke a dangerous permission for an application:

`adb shell pm revoke {{package}} {{permission}}`

- Trigger a key event:

`adb shell input keyevent {{keycode}}`

- Clear the data of an application on an emulator or device:

`adb shell pm clear {{package}}`

- Start an activity on emulator/device:

`adb shell am start -n {{package}}/{{activity}}`

- Start the home activity on an emulator or device:

`adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN`

