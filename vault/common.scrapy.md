---
id: common.scrapy
title: Scrapy
desc: ''
updated: 1623965016148
created: 1623965016148
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scrapy

> Web-crawling framework.
> More information: <https://scrapy.org>.

- Create a project:

`scrapy startproject {{project_name}}`

- Create a spider (in project directory):

`scrapy genspider {{spider_name}} {{website_domain}}`

- Edit spider (in project directory):

`scrapy edit {{spider_name}}`

- Run spider (in project directory):

`scrapy crawl {{spider_name}}`

- Fetch a webpage as scrapy sees it and print source in stdout:

`scrapy fetch {{url}}`

- Open a webpage in the default browser as scrapy sees it (disable JavaScript for extra fidelity):

`scrapy view {{url}}`

- Open scrapy shell for URL, which allows interaction with the page source in python shell (or ipython if available):

`scrapy shell {{url}}`

