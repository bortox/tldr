---
author: ['Axel Navarro']
date: 1645436403
title: "standard-version"
description: "standard-version, Automate versioning and changelog generation, with SemVer and Conventional Commits."
categories: "common"
---
> More information: <https://github.com/conventional-changelog/standard-version>.

- Update the changelog file and tag a release:

```bash
standard-version
```

- Tag a release without bumping the version:

```bash
standard-version --first-release
```

- Update the changelog and tag an alpha release:

```bash
standard-version --prerelease alpha
```

- Update the changelog and tag a specific release type:

```bash
standard-version --release-as major|minor|patch
```

- Tag a release, preventing hooks from being verified during the commit step:

```bash
standard-version --no-verify
```

- Tag a release committing all staged changes, not just files affected by `standard-version`:

```bash
standard-version --commit-all
```

- Update a specific changelog file and tag a release:

```bash
standard-version --infile path/to/file.md
```

- Display the release that would be performed without performing them:

```bash
standard-version --dry-run
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | standard-version: add page (#7753) | 2022-02-21T10:40:03 | [139450a866fa](https://github.com/tldr-pages/tldr/commit/139450a866fa9a6904a150abc02cbbd6c00e1a79)

