---
id: common.in2csv
title: In2csv
desc: ''
updated: 1615655543064
created: 1615655543064
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

