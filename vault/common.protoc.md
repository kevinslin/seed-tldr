---
id: common.protoc
title: Protoc
desc: ''
updated: 1642441815061
created: 1642441815061
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# protoc

> Parse Google Protobuf `.proto` files and generate output in the specified language.
> More information: <https://developers.google.com/protocol-buffers>.

- Generate Python code from a `.proto` file:

`protoc --python_out={{path/to/output_directory}} {{input_file.proto}}`

- Generate Java code from a `.proto` file that imports other `.proto` files:

`protoc --java_out={{path/to/output_directory}} --proto_path={{path/to/import_search_path}} {{input_file.proto}}`

- Generate code for multiple languages:

`protoc --csharp_out={{path/to/c#_output_directory}} --js_out={{path/to/js_output_directory}} {{input_file.proto}}`

