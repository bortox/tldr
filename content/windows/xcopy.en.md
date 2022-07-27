---
author: ['Marco Bonelli', 'Owen Voke']
date: 1609243325
title: "xcopy, TLDR Pages"
description: "xcopy, Copy files and directory trees."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/xcopy>.

- Copy the file(s) to the specified destination:

```bash
xcopy path/to/file_or_directory path/to/destination
```

- List files that will be copied before copying:

```bash
xcopy path/to/file_or_directory path/to/destination /p
```

- Copy the directory structure only, excluding files:

```bash
xcopy path/to/file_or_directory path/to/destination /t
```

- Include empty directories when copying:

```bash
xcopy path/to/file_or_directory path/to/destination /e
```

- Keep the source ACL in the destination:

```bash
xcopy path/to/file_or_directory path/to/destination /o
```

- Allow resuming when network connection is lost:

```bash
xcopy path/to/file_or_directory path/to/destination /z
```

- Disable the prompt when the file exists in the destination:

```bash
xcopy path/to/file_or_directory path/to/destination /y
```

- Display detailed usage information:

```bash
xcopy /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | xcopy: add more information link | 2020-12-29T13:02:05 | [f28681dd3684](https://github.com/tldr-pages/tldr/commit/f28681dd3684c5cc37785d30f251d40bc3a43a7c)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Owen Voke](mailto:owzie123@gmail.com) | xcopy: add page (#2084) | 2018-05-03T18:35:50 | [ccb73597b131](https://github.com/tldr-pages/tldr/commit/ccb73597b131818a25122011da8ebb5e4614a39f)

