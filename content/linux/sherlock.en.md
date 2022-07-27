---
author: ['Bhargav Das Gupta']
date: 1641408646
title: "sherlock, TLDR Pages"
description: "sherlock, Find usernames across social networks."
categories: "linux"
---
> More information: <https://github.com/sherlock-project/sherlock>.

- Search for a specific username on social networks saving the results to a file:

```bash
sherlock username --output path/to/file
```

- Search for specific usernames on social networks saving the results into a directory:

```bash
sherlock username1 username2 ... --folderoutput path/to/directory
```

- Search for a specific username on social networks using the Tor network:

```bash
sherlock --tor username
```

- Make requests over Tor with a new Tor circuit after each request:

```bash
sherlock --unique-tor username
```

- Search for a specific username on social networks using a proxy:

```bash
sherlock username --proxy proxy_url
```

- Search for a specific username on social networks and open results in the default web browser:

```bash
sherlock username --browse
```

- Display help:

```bash
sherlock --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bhargav Das Gupta](mailto:47706967+Hephaestus14089@users.noreply.github.com) | sherlock: add page (#7609) | 2022-01-05T19:50:46 | [a156709d73bf](https://github.com/tldr-pages/tldr/commit/a156709d73bfba6585a2e85e48c1a920e8224cdf)

