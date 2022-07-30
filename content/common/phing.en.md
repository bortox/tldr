---
author: ['pxgamer', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1656325392
title: "phing"
description: "phing, A PHP build tool based on Apache Ant."
categories: "common"
---
> More information: <https://www.phing.info>.

- Perform the default task in the `build.xml` file:

```bash
phing
```

- Initialize a new build file:

```bash
phing -i path/to/build.xml
```

- Perform a specific task:

```bash
phing task_name
```

- Specify a custom build file path:

```bash
phing -f path/to/build.xml task_name
```

- Specify a log file to output to:

```bash
phing -b path/to/log_file task_name
```

- Specify custom properties to use in the build:

```bash
phing -Dproperty=value task_name
```

- Specify a custom listener class:

```bash
phing -listener class_name task_name
```

- Build using verbose output:

```bash
phing -verbose task_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | phing: add link to homepage | 2019-05-31T20:47:40 | [6e81f3c81350](https://github.com/tldr-pages/tldr/commit/6e81f3c81350b8dc0632a678805690b84882a188)
[pxgamer](mailto:owzie123@gmail.com) | phing: update wording of log example | 2018-12-19T07:22:26 | [efee70a0724c](https://github.com/tldr-pages/tldr/commit/efee70a0724c898d78694731173597e966ae92bd)
[pxgamer](mailto:owzie123@gmail.com) | phing: add page | 2018-12-19T07:22:26 | [cc0a81671c2b](https://github.com/tldr-pages/tldr/commit/cc0a81671c2bbd82ed34f6d546a84a7bbca91140)

