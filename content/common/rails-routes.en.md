---
author: ['Nelson Figueroa']
date: 1584737847
title: "rails routes"
description: "rails routes, List routes in a Rails application."
categories: "common"
---
> More information: <https://guides.rubyonrails.org/routing.html>.

- List all routes:

```bash
rails routes
```

- List all routes in an expanded format:

```bash
rails routes --expanded
```

- List routes partially matching URL helper method name, HTTP verb, or URL path:

```bash
rails routes -g posts_path|GET|/posts
```

- List routes that map to a specified controller:

```bash
rails routes -c posts|Posts|Blogs::PostsController
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | rails-routes: add page (#3922) | 2020-03-20T21:57:27 | [8aef2d28583c](https://github.com/tldr-pages/tldr/commit/8aef2d28583c4fe64a7367c67d5184acd4039e30)

