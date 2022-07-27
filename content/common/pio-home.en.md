---
author: ['marchersimon']
date: 1616684958
title: "pio home, TLDR Pages"
description: "pio home, Launch the PlatformIO Home web server."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_home.html>.

- Open PlatformIO Home in the default web browser:

```bash
pio home
```

- Use a specific HTTP port (defaults to 8008):

```bash
pio home --port port
```

- Bind to a specific IP address (defaults to 127.0.0.1):

```bash
pio home --host ip_address
```

- Do not automatically open PlatformIO Home in the default web browser:

```bash
pio home --no-open
```

- Automatically shutdown the server on timeout (in seconds) when no clients are connected:

```bash
pio home --shutdown-timeout time
```

- Specify a unique session identifier to keep PlatformIO Home isolated from other instances and protected from 3rd party access:

```bash
pio home --session-id id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-home: add page (#5406) | 2021-03-25T16:09:18 | [0f37d0336b7e](https://github.com/tldr-pages/tldr/commit/0f37d0336b7ed3bbd45890a48a3d49bc39f97cd9)

