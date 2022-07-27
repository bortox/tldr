---
author: ['Giorgio Vilardo']
date: 1595907371
title: "gunicorn, TLDR Pages"
description: "gunicorn, Python WSGI HTTP Server."
categories: "common"
---
> More information: <https://gunicorn.org/>.

- Run Python web app:

```bash
gunicorn import.path:app_object
```

- Listen on port 8080 on localhost:

```bash
gunicorn --bind localhost:8080 import.path:app_object
```

- Turn on live reload:

```bash
gunicorn --reload import.path:app_object
```

- Use 4 worker processes for handling requests:

```bash
gunicorn --workers 4 import.path:app_object
```

- Use 4 worker threads for handling requests:

```bash
gunicorn --threads 4 import.path:app_object
```

- Run app over HTTPS:

```bash
gunicorn --certfile cert.pem --keyfile key.pem import.path:app_object
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Giorgio Vilardo](mailto:56472600+giorgiovilardo@users.noreply.github.com) | gunicorn: moved into common, added website (#4226) | 2020-07-28T05:36:11 | [867bb333ad52](https://github.com/tldr-pages/tldr/commit/867bb333ad52e429b8d0d65be7c6a8e1b318a885)

