---
author: ['Owen Voke', 'Kyle Parrish', 'Michael Schwarz', 'Lucas Gabriel Schneider', 'bl-ue', 'Alistair Young']
date: 1635423455
title: "wsl"
description: "wsl, Manage the Windows Subsystem for Linux from the command-line."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows/wsl/reference>.

- Start a Linux shell (in the default distribution):

```bash
wsl shell_command
```

- Run a Linux command without using a shell:

```bash
wsl --exec command command_arguments
```

- Specify a particular distribution:

```bash
wsl --distribution distribution shell_command
```

- List available distributions:

```bash
wsl --list
```

- Export a distribution to a `.tar` file:

```bash
wsl --export distribution path/to/distro_fs.tar
```

- Import a distribution from a `.tar` file:

```bash
wsl --import distribution path/to/install_location path/to/distro_fs.tar
```

- Change the version of wsl used for the specified distribution:

```bash
wsl --set-version distribution version
```

- Shut down Windows Subsystem for Linux:

```bash
wsl --shutdown
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Michael Schwarz](mailto:michael089+github@outlook.de) | wsl: improve --set-version example description (#7265) | 2021-10-28T14:17:35 | [b6352928ec9c](https://github.com/tldr-pages/tldr/commit/b6352928ec9cfe02759df5d47d95ba0740474163)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Kyle Parrish](mailto:arnydo@gmail.com) | wsl: add --set-version example (#4578) | 2020-10-09T15:00:55 | [1c3164143e58](https://github.com/tldr-pages/tldr/commit/1c3164143e58788aa49794f0382f20243002a212)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Alistair Young](mailto:avatar@arkane-systems.net) | wsl: add page (#3230) | 2019-08-07T20:19:03 | [c5d615e21202](https://github.com/tldr-pages/tldr/commit/c5d615e21202d52ae4b6c2535395207531b4d882)

