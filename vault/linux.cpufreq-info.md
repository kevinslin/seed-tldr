---
id: linux.cpufreq-info
title: Cpufreq Info
desc: ''
updated: 1623965306220
created: 1623965306220
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cpufreq-info

> A tool to show CPU frequency information.

- Show CPU frequency information for all CPUs:

`cpufreq-info`

- Show CPU frequency information for the specified CPU:

`cpufreq-info -c {{cpu_number}}`

- Show the allowed minimum and maximum CPU frequency:

`cpufreq-info -l`

- Show the current minimum and maximum CPU frequency and policy in table format:

`cpufreq-info -o`

- Show available CPU frequency policies:

`cpufreq-info -g`

- Show current CPU work frequency in a human-readable format, according to the cpufreq kernel module:

`cpufreq-info -f -m`

- Show current CPU work frequency in a human-readable format, by reading it from hardware (only available to root):

`sudo cpufreq-info -w -m`

