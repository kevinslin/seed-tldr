---
id: common.xxd
title: Xxd
desc: ''
updated: 1642441815085
created: 1642441815085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xxd

> Create a hexadecimal representation (hexdump) from a binary file, or vice-versa.
> More information: <https://manned.org/xxd>.

- Generate a hexdump from a binary file and display the output:

`xxd {{input_file}}`

- Generate a hexdump from a binary file and save it as a text file:

`xxd {{input_file}} {{output_file}}`

- Display a more compact output, replacing consecutive zeros (if any) with a star:

`xxd -a {{input_file}}`

- Display the output with 10 columns of one octet (byte) each:

`xxd -c {{10}} {{input_file}}`

- Display output only up to a length of 32 bytes:

`xxd -l {{32}} {{input_file}}`

- Display the output in plain mode, without any gaps between the columns:

`xxd -p {{input_file}}`

- Revert a plaintext hexdump back into binary, and save it as a binary file:

`xxd -r -p {{input_file}} {{output_file}}`

