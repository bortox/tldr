---
author: ['marchersimon']
date: 1619890039
title: "pio test"
description: "pio test, Run local tests on a PlatformIO project."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_test.html>.

- Run all tests in all environments of the current PlatformIO project:

```bash
pio test
```

- Test only specific environments:

```bash
pio test --environment environment1 --environment environment2
```

- Run only tests whose name matches a specific glob pattern:

```bash
pio test --filter "pattern"
```

- Ignore tests whose name matches a specific glob pattern:

```bash
pio test --ignore "pattern"
```

- Specify a port for firmware uploading:

```bash
pio test --upload-port upload_port
```

- Specify a custom configuration file for running the tests:

```bash
pio test --project-conf path/to/platformio.ini
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-test: add page (#5815) | 2021-05-01T19:27:19 | [6e6711f2e375](https://github.com/tldr-pages/tldr/commit/6e6711f2e3751ff21b83c1b32a91bee66b96d53e)

