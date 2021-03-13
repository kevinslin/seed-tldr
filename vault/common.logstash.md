---
id: common.logstash
title: Logstash
desc: ''
updated: 1615655543067
created: 1615655543067
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# logstash

> An ETL (extract, transform and load) tool.
> Commonly used to load data from various sources, like databases and log files, into elasticsearch.
> More information: <https://www.elastic.co/products/logstash>.

- Check validity of a logstash configuration:

`logstash --configtest --config {{logstash_config.conf}}`

- Run logstash using configuration:

`sudo logstash --config {{logstash_config.conf}}`

- Run logstash with the most basic inline configuration string:

`sudo logstash -e 'input {} filter {} output {}'`

