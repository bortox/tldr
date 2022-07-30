---
author: ['Matthew Peveler', 'Seth Falco', 'lakhininenina', 'marchersimon']
date: 1658921926
title: "waitress-serve"
description: "waitress-serve, Pure Python WSGI HTTP Server."
categories: "common"
---
> More information: <https://docs.pylonsproject.org/projects/waitress/en/latest/runner.html>.

- Run a Python web app:

```bash
waitress-serve import.path:wsgi_func
```

- Listen on port 8080 on localhost:

```bash
waitress-serve --listen=localhost:8080 import.path:wsgi_func
```

- Start waitress on a Unix socket:

```bash
waitress-serve --unix-socket=path/to/socket import.path:wsgi_func
```

- Use 4 threads to process requests:

```bash
waitress-serve --threads=4 import.path:wsgifunc
```

- Call a factory method that returns a WSGI object:

```bash
waitress-serve --call import.path.wsgi_factory
```

- Set the URL scheme to HTTPS:

```bash
waitress-serve --url-scheme=https import.path:wsgi_func
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: add/edit more information link (#8255) | 2022-07-27T13:38:46 | [df1c9855a704](https://github.com/tldr-pages/tldr/commit/df1c9855a704f1360748c4b7652f8bca1db3a6c7)
[lakhininenina](mailto:99631909+lakhininenina@users.noreply.github.com) | waitress-serve: add more information link (#8128) | 2022-06-15T12:41:55 | [87adc08d60b8](https://github.com/tldr-pages/tldr/commit/87adc08d60b88e1275bb91d96bb3c2315d65b0fe)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Matthew Peveler](mailto:matt.peveler@gmail.com) | waitress-serve: add page (#2451) | 2018-10-16T19:29:26 | [9ef7ec119aee](https://github.com/tldr-pages/tldr/commit/9ef7ec119aee1df3445a25a7bfa1f25c72d69b4b)

