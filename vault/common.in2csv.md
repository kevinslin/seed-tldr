---
id: common.in2csv
title: In2csv
desc: ''
updated: 1615663978719
created: 1615663978719
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# in2csv

> Converts various tabular data formats into CSV.
> Included in csvkit.
> More information: <https://csvkit.readthedocs.io/en/latest/scripts/in2csv.html>.

- Convert an XLS file to CSV:

`in2csv {{data.xls}}`

- Convert a DBF file to a CSV file:

`in2csv {{data.dbf}} > {{data.csv}}`

- Convert a specific sheet from an XLSX file to CSV:

`in2csv --sheet={{sheet_name}} {{data.xlsx}}`

- Pipe a JSON file to in2csv:

`cat {{data.json}} | in2csv -f json > {{data.csv}}`

