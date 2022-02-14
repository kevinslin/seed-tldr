---
id: osx.system_profiler
title: System_profiler
desc: ''
updated: 1644840636313
created: 1644840636313
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# system_profiler

> Report system hardware and software configuration.
> More information: <https://ss64.com/osx/system_profiler.html>.

- Display a full system profiler report which can be opened by System Profiler.app:

`system_profiler -xml > MyReport.spx`

- Display a hardware overview (Model, CPU, Memory, Serial, etc):

`system_profiler SPHardwareDataType`

- Print the system serial number:

`system_profiler SPHardwareDataType|grep "Serial Number (system)" | awk '{ print $4 }'`

