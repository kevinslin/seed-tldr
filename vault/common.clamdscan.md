---
id: common.clamdscan
title: Clamdscan
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
# clamdscan

> A command-line virus scanner using the ClamAV Daemon.
> More information: <https://www.clamav.net>.

- Scan a file or directory for vulnerabilities:

`clamdscan {{path/to/file_or_directory}}`

- Scan data from stdin:

`{{command}} | clamdscan -`

- Scan the current directory and output only infected files:

`clamdscan --infected`

- Output the scan report to a log file:

`clamdscan --log {{path/to/log_file}}`

- Move infected files to a specific directory:

`clamdscan --move {{path/to/quarantine_directory}}`

- Remove infected files:

`clamdscan --remove`

- Use multiple threads to scan a directory:

`clamdscan --multiscan`

- Pass the file descriptor instead of streaming the file to the daemon:

`clamdscan --fdpass`

