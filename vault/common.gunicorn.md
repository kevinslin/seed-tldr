---
id: common.gunicorn
title: Gunicorn
desc: ''
updated: 1623965016131
created: 1623965016131
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gunicorn

> Python WSGI HTTP Server.
> More information: <https://gunicorn.org/>.

- Run Python web app:

`gunicorn {{import.path:app_object}}`

- Listen on port 8080 on localhost:

`gunicorn --bind {{localhost}}:{{8080}} {{import.path:app_object}}`

- Turn on live reload:

`gunicorn --reload {{import.path:app_object}}`

- Use 4 worker processes for handling requests:

`gunicorn --workers {{4}} {{import.path:app_object}}`

- Use 4 worker threads for handling requests:

`gunicorn --threads {{4}} {{import.path:app_object}}`

- Run app over HTTPS&#x3A;

`gunicorn --certfile {{cert.pem}} --keyfile {{key.pem}} {{import.path:app_object}}`

