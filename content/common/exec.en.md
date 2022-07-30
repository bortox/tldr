---
author: ['proxy', 'Marco Bonelli', 'lincc']
date: 1631818200
title: "exec"
description: "exec, Replace the current process with another process."
categories: "common"
---
> More information: <https://linuxcommand.org/lc3_man_pages/exech.html>.

- Replace with the specified command using the current environment variables:

```bash
exec command -with -flags
```

- Replace with the specified command, clearing environment variables:

```bash
exec -c command -with -flags
```

- Replace with the specified command and login using the default shell:

```bash
exec -l command -with -flags
```

- Replace with the specified command and change the process name:

```bash
exec -a process_name command -with -flags
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | exec, javac: add more information link (#6536) | 2021-09-16T20:50:00 | [53bb0828896b](https://github.com/tldr-pages/tldr/commit/53bb0828896bfcca7b5ce118fe241ef20c7a6fb0)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | exec: correct and clarify example descriptions. (#3325) | 2019-10-06T05:34:58 | [b751a31f72ce](https://github.com/tldr-pages/tldr/commit/b751a31f72ce54b1b790d331294a10fccdb57bcd)
[proxy](mailto:42575435+imaiproxy@users.noreply.github.com) | exec: add page (#2800) | 2019-02-25T22:58:36 | [39b9d7b990dd](https://github.com/tldr-pages/tldr/commit/39b9d7b990dd651856a01f80a88b884007bfe4bb)

