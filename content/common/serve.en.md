---
author: ['Axel Navarro']
date: 1644652453
title: "serve, TLDR Pages"
description: "serve, Static file serving and directory listing."
categories: "common"
---
> More information: <https://github.com/vercel/serve>.

- Start an HTTP server listening on the default port to serve the current directory:

```bash
serve
```

- Start an HTTP server on a specific [p]ort to serve a specific directory:

```bash
serve -p port path/to/directory
```

- Start an HTTP server with CORS enabled by including the `Access-Control-Allow-Origin: *` header in all responses:

```bash
serve --cors
```

- Start an HTTP server on the default port rewriting all not-found requests to the `index.html` file:

```bash
serve --single
```

- Start an HTTPS server on the default port using the specified certificate:

```bash
serve --ssl-cert path/to/cert.pem --ssl-key path/to/key.pem
```

- Start an HTTP server on the default port using a specific configuration file:

```bash
serve --config path/to/serve.json
```

- Display help:

```bash
serve --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | serve: add page (#7741) | 2022-02-12T08:54:13 | [8ba9ec2b37f3](https://github.com/tldr-pages/tldr/commit/8ba9ec2b37f308c463bc649051fa34b49b158416)

