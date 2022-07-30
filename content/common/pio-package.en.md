---
author: ['marchersimon']
date: 1618082592
title: "pio package"
description: "pio package, Manage packages in the registry."
categories: "common"
---
> Packages can only be removed within 72 hours (3 days) from the date that they are published.

> More information: <https://docs.platformio.org/en/latest/core/userguide/package/>.

- Create a package tarball from the current directory:

```bash
pio package pack --output path/to/package.tar.gz
```

- Create and publish a package tarball from the current directory:

```bash
pio package publish
```

- Publish the current directory and restrict public access to it:

```bash
pio package publish --private
```

- Publish a package:

```bash
pio package publish path/to/package.tar.gz
```

- Publish a package with a custom release date (UTC):

```bash
pio package publish path/to/package.tar.gz --released-at "2021-04-08 21:15:38"
```

- Remove all versions of a published package from the registry:

```bash
pio package unpublish package_name
```

- Remove a specific version of a published package from the registry:

```bash
pio package unpublish package_name@version
```

- Undo the removal, putting all versions or a specific version of the package back into the registry:

```bash
pio package unpublish --undo package_name@version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-package: add page (#5713) | 2021-04-10T21:23:12 | [3815dd21789b](https://github.com/tldr-pages/tldr/commit/3815dd21789bee0a8a6684772644c1fea1307c1c)

