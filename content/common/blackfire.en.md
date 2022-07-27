---
author: ['Marco Bonelli', 'Seth Falco', 'Owen Voke', 'bl-ue']
date: 1656325392
title: "blackfire, TLDR Pages"
description: "blackfire, A command-line profiling tool for PHP."
categories: "common"
---
> More information: <https://blackfire.io>.

- Initialize and configure the Blackfire client:

```bash
blackfire config
```

- Launch the Blackfire agent:

```bash
blackfire agent
```

- Launch the Blackfire agent on a specific socket:

```bash
blackfire agent --socket="tcp://127.0.0.1:8307"
```

- Run the profiler on a specific program:

```bash
blackfire run php path/to/file.php
```

- Run the profiler and collect 10 samples:

```bash
blackfire --samples=10 run php path/to/file.php
```

- Run the profiler and output results as JSON:

```bash
blackfire --json run php path/to/file.php
```

- Upload a profiler file to the Blackfire web service:

```bash
blackfire upload path/to/file
```

- View the status of profiles on the Blackfire web service:

```bash
blackfire status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | blackfire: add page (#2980) | 2019-05-07T15:51:01 | [5a1f868aa9ad](https://github.com/tldr-pages/tldr/commit/5a1f868aa9ad7dbc2233ac87c4e30587cb084eb2)

