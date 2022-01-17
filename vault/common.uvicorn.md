---
id: common.uvicorn
title: Uvicorn
desc: ''
updated: 1642441815079
created: 1642441815079
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uvicorn

> Python ASGI HTTP Server, for asynchronous projects.
> More information: <https://www.uvicorn.org/>.

- Run Python web app:

`uvicorn {{import.path:app_object}}`

- Listen on port 8080 on localhost:

`uvicorn --host {{localhost}} --port {{8080}} {{import.path:app_object}}`

- Turn on live reload:

`uvicorn --reload {{import.path:app_object}}`

- Use 4 worker processes for handling requests:

`uvicorn --workers {{4}} {{import.path:app_object}}`

- Run app over HTTPS&#x3A;

`uvicorn --ssl-certfile {{cert.pem}} --ssl-keyfile {{key.pem}} {{import.path:app_object}}`

