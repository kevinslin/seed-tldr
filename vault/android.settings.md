---
id: android.settings
title: Settings
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
# settings

> Get information about the Android OS.
> More information: <https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- Display a list of settings in the `global` namespace:

`settings list {{global}}`

- Get the value of a specific setting:

`settings get {{global}} {{airplane_mode_on}}`

- Set the value of a setting:

`settings put {{system}} {{screen_brightness}} {{42}}`

- Delete a specific setting:

`settings delete {{secure}} {{screensaver_enabled}}`

