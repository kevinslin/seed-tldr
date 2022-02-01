---
id: common.phpcbf
title: Phpcbf
desc: ''
updated: 1642441815057
created: 1642441815057
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phpcbf

> Fix violations detected by phpcs.
> More information: <https://github.com/squizlabs/PHP_CodeSniffer>.

- Fix issues in the specified directory (defaults to the PEAR standard):

`phpcbf {{path/to/directory}}`

- Display a list of installed coding standards:

`phpcbf -i`

- Specify a coding standard to validate against:

`phpcbf {{path/to/directory}} --standard {{standard}}`

- Specify comma-separated file extensions to include when sniffing:

`phpcbf {{path/to/directory}} --extensions {{file_extension(s)}}`

- A comma-separated list of files to load before processing:

`phpcbf {{path/to/directory}} --bootstrap {{file(s)}}`

- Don't recurse into subdirectories:

`phpcbf {{path/to/directory}} -l`

