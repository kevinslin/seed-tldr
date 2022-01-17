---
id: common.circup
title: Circup
desc: ''
updated: 1642441815002
created: 1642441815002
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# circup

> The CircuitPython library updater.
> More information: <https://github.com/adafruit/circup>.

- Interactively update modules on a device:

`circup update`

- Install a new library:

`circup install {{library_name}}`

- Search for a library:

`circup show {{partial_name}}`

- List all libraries on a connected device in `requirements.txt` format:

`circup freeze`

- Save all libraries on a connected device in the current directory:

`circup freeze -r`

