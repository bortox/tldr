---
author: ['Axel Navarro']
date: 1632310696
title: "fakeroot"
description: "fakeroot, Run a command in an environment faking root privileges for file manipulation."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/fakeroot/fakeroot.1.html>.

- Start the default shell as fakeroot:

```bash
fakeroot
```

- Run a command as fakeroot:

```bash
fakeroot -- command command_arguments
```

- Run a command as fakeroot and save the environment to a file on exit:

```bash
fakeroot -s path/to/file -- command command_arguments
```

- Load a fakeroot environment and run a command as fakeroot:

```bash
fakeroot -i path/to/file -- command command_arguments
```

- Run a command keeping the real ownership of files instead of pretending they are owned by root:

```bash
fakeroot --unknown-is-real -- command command_arguments
```

- Display help:

```bash
fakeroot --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | fakeroot: add page (#6562) | 2021-09-22T13:38:16 | [05ff190f23c7](https://github.com/tldr-pages/tldr/commit/05ff190f23c749d5cab00ab0bf30eb7ded9f70b5)

