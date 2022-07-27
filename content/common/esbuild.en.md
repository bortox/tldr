---
author: ['Axel Navarro', 'bl-ue']
date: 1624378073
title: "esbuild, TLDR Pages"
description: "esbuild, JavaScript bundler and minifier built for speed."
categories: "common"
---
> More information: <https://esbuild.github.io/>.

- Bundle a JavaScript application and print to stdout:

```bash
esbuild --bundle path/to/file.js
```

- Bundle a JSX application from stdin:

```bash
esbuild --bundle --outfile=path/to/out.js < path/to/file.jsx
```

- Bundle and minify a JSX application with source maps in `production` mode:

```bash
esbuild --bundle --define:process.env.NODE_ENV=\"production\" --minify --sourcemap path/to/file.js
```

- Bundle a JSX application for a comma-separated list of browsers:

```bash
esbuild --bundle --minify --sourcemap --target=chrome58,firefox57,safari11,edge16 path/to/file.jsx
```

- Bundle a JavaScript application for a specific node version:

```bash
esbuild --bundle --platform=node --target=node12 path/to/file.js
```

- Bundle a JavaScript application enabling JSX syntax in `.js` files:

```bash
esbuild --bundle app.js --loader:.js=jsx path/to/file.js
```

- Bundle and serve a JavaScript application on an HTTP server:

```bash
esbuild --bundle --serve=port --outfile=index.js path/to/file.js
```

- Bundle a list of files to an output directory:

```bash
esbuild --bundle --outdir=path/to/output_directory path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | esbuild: fix grammar (#6157) | 2021-06-22T18:07:53 | [f9aac432e986](https://github.com/tldr-pages/tldr/commit/f9aac432e98600fceed232fbb4a9207389a18837)
[Axel Navarro](mailto:navarroaxel@gmail.com) | esbuild: add page (#5207) | 2021-02-01T20:58:57 | [dc1298012cbe](https://github.com/tldr-pages/tldr/commit/dc1298012cbed0c33e992cb7a85cd39901579f48)

