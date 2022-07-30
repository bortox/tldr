---
author: ['Axel Navarro']
date: 1615833168
title: "ncc"
description: "ncc, Compile a Node.js application into a single file."
categories: "common"
---
> Supports TypeScript, binary addons and dynamic requires.

> More information: <https://github.com/vercel/ncc>.

- Bundle a Node.js application:

```bash
ncc build path/to/file.js
```

- Bundle and minify a Node.js application:

```bash
ncc build --minify path/to/file.js
```

- Bundle and minify a Node.js application and generate source maps:

```bash
ncc build --source-map path/to/file.js
```

- Automatically recompile on changes to source files:

```bash
ncc build --watch path/to/file.js
```

- Bundle a Node.js application into a temporary directory and run it for testing:

```bash
ncc run path/to/file.js
```

- Clean the `ncc` cache:

```bash
ncc clean cache
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | ncc: add page (#5447) | 2021-03-15T19:32:48 | [35d4a1337f29](https://github.com/tldr-pages/tldr/commit/35d4a1337f29318ca69809b77e7cb73e755174af)

