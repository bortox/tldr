---
author: ['Eiman', 'Axel Navarro']
date: 1641649180
title: "dpkg-deb, TLDR Pages"
description: "dpkg-deb, Pack, unpack and provide information about Debian archives."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/dpkg/dpkg-deb.html>.

- Display information about a package:

```bash
dpkg-deb --info path/to/file.deb
```

- Display the package's name and version on one line:

```bash
dpkg-deb --show path/to/file.deb
```

- List the package's contents:

```bash
dpkg-deb --contents path/to/file.deb
```

- Extract package's contents into a directory:

```bash
dpkg-deb --extract path/to/file.deb path/to/directory
```

- Create a package from a specified directory:

```bash
dpkg-deb --build path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Eiman](mailto:eimanip@users.noreply.github.com) | dpkg-deb: add page (#4671) | 2020-10-13T00:19:34 | [b22e30026a97](https://github.com/tldr-pages/tldr/commit/b22e30026a9721614a8d2d46e8397ee932124703)

