---
id: common.fastboot
title: Fastboot
desc: ''
updated: 1623965306184
created: 1623965306184
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fastboot

> Communicate with connected Android devices when in bootloader mode (the one place `adb` doesn't work).
> More information: <https://android.googlesource.com/platform/system/core/+/master/fastboot/#fastboot>.

- Unlock the bootloader:

`fastboot oem unlock`

- Relock the bootloader:

`fastboot oem lock`

- Reboot the device from fastboot mode into fastboot mode again:

`fastboot reboot bootloader`

- Flash a given image:

`fastboot flash {{file.zip}}`

- Flash a custom recovery image:

`fastboot flash recovery {{file.img}}`

- Display connected devices:

`fastboot devices`

- Display all information of a device:

`fastboot getvar all`

