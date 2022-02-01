---
id: android.dumpsys
title: Dumpsys
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
# dumpsys

> Provide information about Android system services.
> This command can only be used through `adb shell`.
> More information: <https://developer.android.com/studio/command-line/dumpsys>.

- Get diagnostic output for all system services:

`dumpsys`

- Get diagnostic output for a specific system service:

`dumpsys {{service}}`

- List all services `dumpsys` can give information about:

`dumpsys -l`

- List service-specific arguments for a service:

`dumpsys {{service}} -h`

- Exclude a specific service from the diagnostic output:

`dumpsys --skip {{service}}`

- Specify a timeout period in seconds (defaults to 10s):

`dumpsys -t {{seconds}}`

