---
id: common.exenv
title: Exenv
desc: ''
updated: 1615655543053
created: 1615655543053
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# exenv

> A tool to easily install Elixir versions and manage application environments.
> More information: <https://github.com/exenv/exenv>.

- Display a list of installed versions:

`exenv versions`

- Use a specific version of Elixir across the whole system:

`exenv global {{version}}`

- Use a specific version of Elixir for the current application/project directory:

`exenv local {{version}}`

- Show the currently selected Elixir version:

`exenv {{version}}`

- Install a version of Elixir (requires `elixir-build` plugin <https://github.com/mururu/elixir-build>):

`exenv install {{version}}`

