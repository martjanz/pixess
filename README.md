# Pixess

Pixess is a simple theme for [Hugo](http://gohugo.io/) based on [Pixyll for Hugo](https://github.com/azmelanar/hugo-theme-pixyll) with spanish translated front-end text.

## Features

- Basic tag support.
- Disqus comments supported.
- Google Analytics supported.
- Social links (currently only for twitter).
- [Formspree](http://formspree.io/) for contanct form.
- Pagination support.

Example config:

```toml
languageCode = "es-ar"
contentdir = "content"
publishdir = "public"
builddrafts = false
baseUrl = ""
canonifyurls = true
title = "Pixess"
author = "admin"
theme = "pixess"

[indexes]
  category = "categories"
  tag = "tags"

[params]
  search_engine = true
  google_analytics_id = "XX-XXXXXXXX-X"
  twitter_username = "username"
  disqus_shortname = "sitename"
  paginate = true
```

