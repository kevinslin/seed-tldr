---
id: common.siege
title: Siege
desc: ''
updated: 1642441815069
created: 1642441815069
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# siege

> HTTP loadtesting and benchmarking tool.
> More information: <https://www.joedog.org/siege-manual/>.

- Test a URL with default settings:

`siege {{https://example.com}}`

- Test a list of URLs:

`siege --file {{path/to/url_list.txt}}`

- Test list of URLs in a random order (Simulates internet traffic):

`siege --internet --file {{path/to/url_list.txt}}`

- Benchmark a list of URLs (without waiting between requests):

`siege --benchmark --file {{path/to/url_list.txt}}`

- Set the amount of concurrent connections:

`siege --concurrent={{50}} --file {{path/to/url_list.txt}}`

- Set how long for the siege to run for:

`siege --time={{30s}} --file {{path/to/url_list.txt}}`

