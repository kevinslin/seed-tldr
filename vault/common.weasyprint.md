---
id: common.weasyprint
title: Weasyprint
desc: ''
updated: 1642441815083
created: 1642441815083
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# weasyprint

> Render HTML to PDF or PNG.
> More information: <https://weasyprint.org/>.

- Render an HTML file to PDF:

`weasyprint {{path/to/input.html}} {{path/to/output}}.pdf`

- Render an HTML file to PNG, including an additional user stylesheet:

`weasyprint {{path/to/input.html}} {{path/to/output}}.png --stylesheet {{path/to/stylesheet.css}}`

- Output additional debugging information when rendering:

`weasyprint {{path/to/input.html}} {{path/to/output}}.pdf --verbose`

- Specify a custom resolution when outputting to PNG:

`weasyprint {{path/to/input.html}} {{path/to/output}}.png --resolution {{300}}`

- Specify a base URL for relative URLs in the input HTML file:

`weasyprint {{path/to/input.html}} {{path/to/output}}.png --base-url {{url_or_filename}}`

