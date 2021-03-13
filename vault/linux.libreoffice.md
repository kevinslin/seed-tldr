---
id: linux.libreoffice
title: Libreoffice
desc: ''
updated: 1615655543103
created: 1615655543103
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# libreoffice

> CLI for the powerful and free office suite LibreOffice.
> More information: <https://www.libreoffice.org/>.

- Open a space-separated list of files in read-only mode:

`libreoffice --view {{path/to/file1}} {{path/to/file2}}`

- Display the content of specific files:

`libreoffice --cat {{path/to/file1}} {{path/to/file2}}`

- Print files to a specific printer:

`libreoffice --pt {{printer_name}} {{path/to/file1}} {{path/to/file2}}`

- Convert all `.doc` files in current directory to pdf:

`libreoffice --convert-to {{pdf}} {{*.doc}}`

