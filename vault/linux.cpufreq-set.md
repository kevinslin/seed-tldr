---
id: linux.cpufreq-set
title: Cpufreq Set
desc: ''
updated: 1623965016159
created: 1623965016159
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cpufreq-set

> A tool to modify CPU frequency settings.
> The frequency value should range between the output of command `cpufreq-info -l`.

- Set the CPU frequency policy of CPU 1 to "userspace":

`sudo cpufreq-set -c {{1}} -g {{userspace}}`

- Set the current minimum CPU frequency of CPU 1:

`sudo cpufreq-set -c {{1}} --min {{min_frequency}}`

- Set the current maximum CPU frequency of CPU 1:

`sudo cpufreq-set -c {{1}} --max {{max_frequency}}`

- Set the current work frequency of CPU 1:

`sudo cpufreq-set -c {{1}} -f {{work_frequency}}`

