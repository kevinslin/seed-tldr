---
id: common.swagger-codegen
title: Swagger Codegen
desc: ''
updated: 1642441815074
created: 1642441815074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# swagger-codegen

> Generate code and documentation for your REST api from a OpenAPI/swagger definition.
> More information: <https://github.com/swagger-api/swagger-codegen>.

- Generate documentation and code from an OpenAPI/swagger file:

`swagger-codegen generate -i {{swagger_file}} -l {{language}}`

- Generate Java code using the library retrofit2 and the option useRxJava2:

`swagger-codegen generate -i {{http://petstore.swagger.io/v2/swagger.json}} -l {{java}} --library {{retrofit2}} -D{{useRxJava2}}={{true}}`

- List available languages:

`swagger-codegen langs`

- Display help options for the generate command:

`swagger-codegen help {{generate}}`

