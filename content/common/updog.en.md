---
author: ['Wizmon2', 'Seth Falco']
date: 1648358715
title: "updog, TLDR Pages"
description: "updog, A replacement for Python's SimpleHTTPServer."
categories: "common"
---
> It allows uploading and downloading via HTTP/S, can set ad hoc SSL certificates and use HTTP basic auth.

> More information: <https://github.com/sc0tfree/updog>.

- Start a HTTP server for the current directory:

```bash
updog
```

- Start a HTTP server for a specified directory:

```bash
updog --directory /path/to/directory
```

- Start a HTTP server on a specified port:

```bash
updog --port port
```

- Start a HTTP server with a password (To log in, leave the username blank and enter the password in the password field):

```bash
updog --password password
```

- Enable transport encryption via SSL:

```bash
updog --ssl
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Wizmon2](mailto:70430759+Wizmon2@users.noreply.github.com) | updog: add page (#6322) | 2021-08-17T22:08:32 | [b37f341b5877](https://github.com/tldr-pages/tldr/commit/b37f341b5877f0753c7d0bab6af3a5eeffe19854)

