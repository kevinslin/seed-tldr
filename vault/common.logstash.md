---
id: common.logstash
title: Logstash
desc: ''
updated: 1642441815042
created: 1642441815042
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# logstash

> An Elasticsearch ETL (extract, transform and load) tool.
> Commonly used to load data from various sources (such as databases and log files) into Elasticsearch.
> More information: <https://www.elastic.co/products/logstash>.

- Check validity of a Logstash configuration:

`logstash --configtest --config {{logstash_config.conf}}`

- Run Logstash using configuration:

`sudo logstash --config {{logstash_config.conf}}`

- Run Logstash with the most basic inline configuration string:

`sudo logstash -e 'input {} filter {} output {}'`

