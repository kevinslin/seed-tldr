---
id: common.monop
title: Monop
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# monop

> Finds and displays signatures of Types and methods inside .NET assemblies.

- Show the structure of a Type built-in of the .NET Framework:

`monop {{System.String}}`

- List the types in an assembly:

`monop -r:{{path/to/assembly.exe}}`

- Show the structure of a Type in a specific assembly:

`monop -r:{{path/to/assembly.dll}} {{Namespace.Path.To.Type}}`

- Only show members defined in the specified Type:

`monop -r:{{path/to/assembly.dll}} --only-declared {{Namespace.Path.To.Type}}`

- Show private members:

`monop -r:{{path/to/assembly.dll}} --private {{Namespace.Path.To.Type}}`

- Hide obsolete members:

`monop -r:{{path/to/assembly.dll}} --filter-obsolete {{Namespace.Path.To.Type}}`

- List the other assemblies that a specified assembly references:

`monop -r:{{path/to/assembly.dll}} --refs`

