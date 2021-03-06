---
id: common.sha224sum
title: Sha224sum
desc: ''
updated: 1623965306209
created: 1623965306209
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sha224sum

> Calculate SHA224 cryptographic checksums.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- Calculate the SHA224 checksum for a file:

`sha224sum {{filename1}}`

- Calculate SHA224 checksums for multiple files:

`sha224sum {{filename1}} {{filename2}}`

- Calculate and save the list of SHA224 checksums to a file:

`sha224sum {{filename1}} {{filename2}} > {{filename.sha224}}`

- Read a file of SHA224 sums and verify all files have matching checksums:

`sha224sum --check {{filename.sha224}}`

- Only show a message for files for which verification fails:

`sha224sum --check --quiet {{filename.sha224}}`

