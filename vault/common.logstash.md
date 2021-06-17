---
id: common.logstash
title: Logstash
desc: ''
updated: 1623965016135
created: 1623965016135
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

- Check validity of a logstash configuration:

`logstash --configtest --config {{logstash_config.conf}}`

- Run logstash using configuration:

`sudo logstash --config {{logstash_config.conf}}`

- Run logstash with the most basic inline configuration string:

`sudo logstash -e 'input {} filter {} output {}'`

