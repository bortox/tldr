---
author: ['NNRepos', 'Owen Voke']
date: 1600794415
title: "tskill, TLDR Pages"
description: "tskill, Ends a process running in a session on a Remote Desktop Session Host."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/tskill>.

- Terminate a process by its process identifier:

```bash
tskill process_id
```

- Terminate a process by its name:

```bash
tskill process_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[NNRepos](mailto:45516943+NNRepos@users.noreply.github.com) | tskill: add page (#3505) Might be worth to mention this command was removed from windows 10, and unlike taskkill, does not require the [...] | 2019-10-30T18:27:21 | [8b87e5f8285f](https://github.com/tldr-pages/tldr/commit/8b87e5f8285fd5b9d06fea143745d10abfb57ed9)

