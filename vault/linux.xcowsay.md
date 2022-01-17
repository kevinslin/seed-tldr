---
id: linux.xcowsay
title: Xcowsay
desc: ''
updated: 1642441815118
created: 1642441815118
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xcowsay

> Display a cute cow and message on your Linux desktop.
> The cow is displayed for either a fixed amount of time, or an amount of time calculated from the size of the text. Click on the cow to dismiss it immediately.
> More information: <https://www.doof.me.uk/xcowsay/>.

- Display a cow saying "hello, world":

`xcowsay "{{hello, world}}"`

- Display a cow with output from another command:

`ls | xcowsay`

- Display a cow at the specified X and Y coordinates:

`xcowsay --at={{X}},{{Y}}`

- Display a different sized cow:

`xcowsay --cow-size={{small|med|large}}`

- Display a thought bubble instead of a speech bubble:

`xcowsay --think`

- Display a different image instead of the default cow:

`xcowsay --image={{path/to/file}}`

