---
id: osx.pod
title: Pod
desc: ''
updated: 1615663978760
created: 1615663978760
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pod

> Dependency manager for Swift and Objective-C Cocoa projects.

- Create a Podfile for the current project with the default contents:

`pod init`

- Download and install all pods defined in the Podfile (that haven't been installed before):

`pod install`

- List all available pods:

`pod list`

- Show the outdated pods (of those currently installed):

`pod outdated`

- Update all currently installed pods to their newest version:

`pod update`

- Update a specific (previously installed) pod to its newest version:

`pod update {{pod_name}}`

- Remove CocoaPods from a Xcode project:

`pod deintegrate {{xcode_project}}`

