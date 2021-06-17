---
id: linux.httpie
title: Httpie
desc: ''
updated: 1623965306223
created: 1623965306223
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# httpie

> A user friendly command-line HTTP tool.

- Send a GET request (default method with no request data):

`http {{https://example.com}}`

- Send a POST request (default method with request data):

`http {{https://example.com}} {{hello=World}}`

- Send a POST request with redirected input:

`http {{https://example.com}} < {{file.json}}`

- Send a PUT request with a given json body:

`http PUT {{https://example.com/todos/7}} {{hello=world}}`

- Send a DELETE request with a given request header:

`http DELETE {{https://example.com/todos/7}} {{API-Key:foo}}`

- Show the whole HTTP exchange (both request and response):

`http -v {{https://example.com}}`

- Download a file:

`http --download {{https://example.com}}`

