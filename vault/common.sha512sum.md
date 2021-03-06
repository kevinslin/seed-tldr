---
id: common.sha512sum
title: Sha512sum
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
# sha512sum

> Calculate SHA512 cryptographic checksums.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- Calculate the SHA512 checksum for a file:

`sha512sum {{filename1}}`

- Calculate SHA512 checksums for multiple files:

`sha512sum {{filename1}} {{filename2}}`

- Calculate and save the list of SHA512 checksums to a file:

`sha512sum {{filename1}} {{filename2}} > {{filename.sha512}}`

- Read a file of SHA512 sums and verify all files have matching checksums:

`sha512sum --check {{filename.sha512}}`

- Only show a message for files for which verification fails:

`sha512sum --check --quiet {{filename.sha512}}`

