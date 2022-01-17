---
id: common.dart
title: Dart
desc: ''
updated: 1642441815007
created: 1642441815007
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dart

> The tool for managing Dart projects.
> More information: <https://dart.dev/tools/dart-tool>.

- Initialize a new Dart project in a directory of the same name:

`dart create {{project_name}}`

- Run a Dart file:

`dart run {{path/to/file.dart}}`

- Download dependencies for the current project:

`dart pub get`

- Run unit tests for the current project:

`dart test`

- Update an outdated project's dependencies to support null-safety:

`dart pub upgrade --null-safety`

- Compile a Dart file to a native binary:

`dart compile exe {{path/to/file.dart}}`

