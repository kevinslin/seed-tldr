---
id: linux.powerstat
title: Powerstat
desc: ''
updated: 1642441815108
created: 1642441815108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# powerstat

> Measures the power consumption of a computer that has a battery power source or supports the RAPL interface.
> More information: <https://manned.org/powerstat>.

- Measure power with the default of 10 samples with an interval of 10 seconds:

`powerstat`

- Measure power with custom number of samples and interval duration:

`powerstat {{interval}} {{number_of_samples}}`

- Measure power using Intel's RAPL interface:

`powerstat -R {{interval}} {{number_of_samples}}`

- Show a histogram of the power measurements:

`powerstat -H {{interval}} {{number_of_samples}}`

- Enable all statistics gathering options:

`powerstat -a {{interval}} {{number_of_samples}}`

