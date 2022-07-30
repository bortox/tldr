---
author: ['Adar', 'Seth Falco']
date: 1629050349
title: "swupd"
description: "swupd, Package management utility for Clear Linux."
categories: "linux"
---
> More information: <https://docs.01.org/clearlinux/latest/guides/clear/swupd.html>.

- Update to the latest version:

```bash
sudo swupd update
```

- Show current version, and check whether a newer one exists:

```bash
swupd check-update
```

- List installed bundles:

```bash
swupd bundle-list
```

- Locate the bundle where a wanted package exists:

```bash
swupd search -b package
```

- Install a new bundle:

```bash
sudo swupd bundle-add bundle
```

- Remove a bundle:

```bash
sudo swupd bundle-remove bundle
```

- Correct broken or missing files:

```bash
sudo swupd verify
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Adar](mailto:9392566+rqj@users.noreply.github.com) | swupd: add page (#4605) | 2020-10-11T07:56:35 | [c38ba9528c2f](https://github.com/tldr-pages/tldr/commit/c38ba9528c2f5ad5e359234a3271d19ded762716)

