---
id: linux.feedreader
title: Feedreader
desc: ''
updated: 1615655543100
created: 1615655543100
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# feedreader

> A GUI desktop RSS client.
> More information: <https://jangernert.github.io/FeedReader/>.

- Print the count of unread articles:

`feedreader --unreadCount`

- Add a URL for a feed to follow:

`feedreader --addFeed={{feed_url}}`

- Grab a specific article using its URL:

`feedreader --grabArticle={{article_url}}`

- Download all images from a specific article:

`feedreader --url={{feed_url}} --grabImages={{article_path}}`

- Play media from a URL:

`feedreader --playMedia={{article_url}}`

