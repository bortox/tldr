---
author: ['Axel Navarro']
date: 1636482935
title: "http-server-upload, TLDR Pages"
description: "http-server-upload, Zero-configuration command-line HTTP server which provides a lightweight interface to upload files."
categories: "common"
---
> More information: <https://github.com/crycode-de/http-server-upload>.

- Start an HTTP server on the default port to upload files to the current directory:

```bash
http-server-upload
```

- Start an HTTP server with the specified maximum allowed file size for uploads in MiB (defaults to 200 MiB):

```bash
MAX_FILE_SIZE=size_in_megabytes http-server-upload
```

- Start an HTTP server on a specific port to upload files to the current directory:

```bash
PORT=port http-server-upload
```

- Start an HTTP server, storing the uploaded files in a specific directory:

```bash
UPLOAD_DIR=path/to/directory http-server-upload
```

- Start an HTTP server using a specific directory to temporarily store files during the upload process:

```bash
UPLOAD_TMP_DIR=path/to/directory http-server-upload
```

- Start an HTTP server accepting uploads with a specific token field in the HTTP post:

```bash
TOKEN=secret http-server-upload
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | http-server-upload: add page (#7201) | 2021-11-09T19:35:35 | [1805d780f250](https://github.com/tldr-pages/tldr/commit/1805d780f250a5802830933636d95dd7f762121d)

