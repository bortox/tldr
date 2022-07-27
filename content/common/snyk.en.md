---
author: ['Dar Malovani', 'marchersimon']
date: 1620952935
title: "snyk, TLDR Pages"
description: "snyk, Find vulnerabilities in your code and remediate risks."
categories: "common"
---
> More information: <https://snyk.io>.

- Log in to your Snyk account:

```bash
snyk auth
```

- Test your code for any known vulnerabilities:

```bash
snyk test
```

- Test a local Docker image for any known vulnerabilities:

```bash
snyk test --docker docker_image
```

- Record the state of dependencies and any vulnerabilities on snyk.io:

```bash
snyk monitor
```

- Auto patch and ignore vulnerabilities:

```bash
snyk wizard
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Dar Malovani](mailto:dar@snyk.io) | snyk: add missing `test` command on the docker option (#3167) | 2019-07-03T15:47:55 | [00444f82fd96](https://github.com/tldr-pages/tldr/commit/00444f82fd96f502f41a4373dc565970c0e80edb)
[Dar Malovani](mailto:dar@snyk.io) | snyk: add page (#3098) | 2019-06-09T03:31:57 | [e00d7f00164d](https://github.com/tldr-pages/tldr/commit/e00d7f00164dbbe42d7c1bdaa609aebea0676083)

