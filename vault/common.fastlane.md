---
id: common.fastlane
title: Fastlane
desc: ''
updated: 1615655543054
created: 1615655543054
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# fastlane

> Build and release mobile applications from the command-line.
> More information: <https://docs.fastlane.tools/actions/>.

- Build and sign the iOS application in the current directory:

`fastlane run build_app`

- Run `pod install` for the project in the current directory:

`fastlane run cocoapods`

- Delete the derived data from Xcode:

`fastlane run clear_derived_data`

- Remove the cache for pods:

`fastlane run clean_cocoapods_cache`

