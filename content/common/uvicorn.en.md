---
author: ['Giorgio Vilardo', 'Axel Navarro']
date: 1609624031
title: "uvicorn"
description: "uvicorn, Python ASGI HTTP Server, for asynchronous projects."
categories: "common"
---
> More information: <https://www.uvicorn.org/>.

- Run Python web app:

```bash
uvicorn import.path:app_object
```

- Listen on port 8080 on localhost:

```bash
uvicorn --host localhost --port 8080 import.path:app_object
```

- Turn on live reload:

```bash
uvicorn --reload import.path:app_object
```

- Use 4 worker processes for handling requests:

```bash
uvicorn --workers 4 import.path:app_object
```

- Run app over HTTPS:

```bash
uvicorn --ssl-certfile cert.pem --ssl-keyfile key.pem import.path:app_object
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | uvicorn: remove trailing space in title line | 2021-01-02T22:47:11 | [3ee0d9049cf9](https://github.com/tldr-pages/tldr/commit/3ee0d9049cf9c1ad8cae7e19cc6177ead5f298a3)
[Giorgio Vilardo](mailto:56472600+giorgiovilardo@users.noreply.github.com) | uvicorn: add page (#4217) | 2020-07-24T22:00:36 | [22577ba81099](https://github.com/tldr-pages/tldr/commit/22577ba81099330d55a19d207d2097d6fa778c06)

