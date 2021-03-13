---
id: common.csvclean
title: Csvclean
desc: ''
updated: 1615655543049
created: 1615655543049
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# csvclean

> Finds and cleans common syntax errors in CSV files.
> Included in csvkit.
> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvclean.html>.

- Clean a CSV file:

`csvclean {{bad.csv}}`

- List locations of syntax errors in a CSV file:

`csvclean -n {{bad.csv}}`

