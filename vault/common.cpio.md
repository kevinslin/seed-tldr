---
id: common.cpio
title: Cpio
desc: ''
updated: 1642441815004
created: 1642441815004
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cpio

> Copies files in and out of archives.
> Supports the following archive formats: cpio's custom binary, old ASCII, new ASCII, crc, HPUX binary, HPUX old ASCII, old tar, and POSIX.1 tar.
> More information: <https://www.gnu.org/software/cpio>.

- Take a list of file names from standard input and add them [o]nto an archive in cpio's binary format:

`echo "{{file1}} {{file2}} {{file3}}" | cpio -o > {{archive.cpio}}`

- Copy all files and directories in a directory and add them [o]nto an archive, in [v]erbose mode:

`find {{path/to/directory}} | cpio -ov > {{archive.cpio}}`

- P[i]ck all files from an archive, generating [d]irectories where needed, in [v]erbose mode:

`cpio -idv < {{archive.cpio}}`

