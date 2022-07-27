---
author: ['Axel Navarro']
date: 1627868032
title: "gh browse, TLDR Pages"
description: "gh browse, Open a GitHub repository in the browser or print the URL."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_browse>.

- Open the homepage of the current repository in the default web browser:

```bash
gh browse
```

- Open the homepage of a specific repository in the default web browser:

```bash
gh browse owner/repository
```

- Open the settings page of the current repository in the default web browser:

```bash
gh browse --settings
```

- Open the wiki of the current repository in the default web browser:

```bash
gh browse --wiki
```

- Open a specific issue or pull request in the web browser:

```bash
gh browse issue_or_pull_request_number
```

- Open a specific branch in the web browser:

```bash
gh browse --branch branch_name
```

- Open a specific file or directory of the current repository in the web browser:

```bash
gh browse path_from_root_of_repository
```

- Print the destination URL without open the web browser:

```bash
gh browse --no-browser
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-browse: add page (#6281) | 2021-08-02T03:33:52 | [124fb797bb96](https://github.com/tldr-pages/tldr/commit/124fb797bb968ca9c07237ec5aed93153cf8711f)

