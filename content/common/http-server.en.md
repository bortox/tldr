---
author: ['Axel Navarro']
date: 1636451951
title: "http-server"
description: "http-server, Simple static HTTP server to serve static files."
categories: "common"
---
> More information: <https://github.com/http-party/http-server>.

- Start an HTTP server listening on the default port to serve the current directory:

```bash
http-server
```

- Start an HTTP server on a specific port to serve a specific directory:

```bash
http-server path/to/directory --port port
```

- Start an HTTP server using basic authentication:

```bash
http-server --username username --password password
```

- Start an HTTP server with directory listings disabled:

```bash
http-server -d false
```

- Start an HTTPS server on the default port using the specified certificate:

```bash
http-server --ssl --cert path/to/cert.pem --key path/to/key.pem
```

- Start an HTTP server and include the client's IP address in the output logging:

```bash
http-server --log-ip
```

- Start an HTTP server with CORS enabled by including the `Access-Control-Allow-Origin: *` header in all responses:

```bash
http-server --cors
```

- Start an HTTP server with logging disabled:

```bash
http-server --silent
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | http-server: add page (#7200) | 2021-11-09T10:59:11 | [9cdd92e3c39b](https://github.com/tldr-pages/tldr/commit/9cdd92e3c39b517924078e5b0db8d3f1075ca450)

