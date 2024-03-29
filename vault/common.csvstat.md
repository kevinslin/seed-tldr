---
id: common.csvstat
title: Csvstat
desc: ''
updated: 1642441815005
created: 1642441815005
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csvstat

> Print descriptive statistics for all columns in a CSV file.
> Included in csvkit.
> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvstat.html>.

- Show all stats for all columns:

`csvstat {{data.csv}}`

- Show all stats for columns 2 and 4:

`csvstat -c {{2,4}} {{data.csv}}`

- Show sums for all columns:

`csvstat --sum {{data.csv}}`

- Show the max value length for column 3:

`csvstat -c {{3}} --len {{data.csv}}`

- Show the number of unique values in the "name" column:

`csvstat -c {{name}} --unique {{data.csv}}`

