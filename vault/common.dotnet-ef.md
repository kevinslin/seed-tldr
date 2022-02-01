---
id: common.dotnet-ef
title: Dotnet Ef
desc: ''
updated: 1642441815010
created: 1642441815010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dotnet ef

> Perform design-time development tasks for Entity Framework Core.
> More information: <https://docs.microsoft.com/ef/core/cli/dotnet>.

- Update the database to a specified migration:

`dotnet ef database update {{migration}}`

- Drop the database:

`dotnet ef database drop`

- List available `DbContext` types:

`dotnet ef dbcontext list`

- Generate code for a `DbContext` and entity types for a database:

`dotnet ef dbcontext scaffold {{connection_string}} {{provider}}`

- Add a new migration:

`dotnet ef migrations add {{name}}`

- Remove the last migration, rolling back the code changes that were done for the latest migration:

`dotnet ef migrations remove`

- List available migrations:

`dotnet ef migrations list`

- Generate a SQL script from migrations range:

`dotnet ef migrations script {{from_migration}} {{to_migration}}`

