---
author: ['Snehit Sah']
date: 1633502173
title: "cvs"
description: "cvs, Concurrent Versions System, a revision control system."
categories: "common"
---
> More information: <https://cvs.nongnu.org>.

- Create a new repository (requires the `CVSROOT` environment variable to be set externally):

```bash
cvs -d path/to/repository init
```

- Add a project to the repository:

```bash
cvs import -m "message" project_name version vendor
```

- Checkout a project:

```bash
cvs checkout project_name
```

- Show changes made to files:

```bash
cvs diff path/to/file
```

- Add a file:

```bash
cvs add path/to/file
```

- Commit a file:

```bash
cvs commit -m "message" path/to/file
```

- Update the working directory from the remote repository:

```bash
cvs update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Snehit Sah](mailto:snehitsah@protonmail.com) | cvs: add page (#6625) | 2021-10-06T08:36:13 | [c4bdc2bb5af4](https://github.com/tldr-pages/tldr/commit/c4bdc2bb5af440663e01071484ec6f395e5ca7cc)

