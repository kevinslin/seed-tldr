---
id: common.influx
title: Influx
desc: ''
updated: 1642441815035
created: 1642441815035
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# influx

> InfluxDB command-line client.
> More information: <https://docs.influxdata.com/influxdb/v1.7/tools/shell/>.

- Connect to an InfluxDB running on localhost with no credentials:

`influx`

- Connect with a specific username (will prompt for a password):

`influx -username {{username}} -password ""`

- Connect to a specific host:

`influx -host {{hostname}}`

- Use a specific database:

`influx -database {{database_name}}`

- Execute a given command:

`influx -execute "{{influxql_command}}"`

- Return output in a specific format:

`influx -execute "{{influxql_command}}" -format {{json|csv|column}}`

