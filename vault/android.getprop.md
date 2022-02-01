---
id: android.getprop
title: Getprop
desc: ''
updated: 1642441814990
created: 1642441814990
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# getprop

> Show information about Android system properties.
> More information: <https://manned.org/getprop>.

- Display information about Android system properties:

`getprop`

- Display information about a specific property:

`getprop {{prop}}`

- Display the SDK API level:

`getprop {{ro.build.version.sdk}}`

- Display the Android version:

`getprop {{ro.build.version.release}}`

- Display the Android device model:

`getprop {{ro.vendor.product.model}}`

- Display the OEM unlock status:

`getprop {{ro.oem_unlock_supported}}`

- Display the MAC address of the Android's Wi-Fi card:

`getprop {{ro.boot.wifimacaddr}}`

