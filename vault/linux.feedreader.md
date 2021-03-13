---
id: linux.feedreader
title: Feedreader
desc: ''
updated: 1615663978746
created: 1615663978746
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

