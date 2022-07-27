---
author: ['Nir Elbaz', 'Jose Lemus', 'pxgamer', 'Igor Shubovych', 'CleanMachine1', 'Ray Voice']
date: 1627481407
title: "nano, TLDR Pages"
description: "nano, Simple, easy to use command-line text editor. An enhanced, free Pico clone."
categories: "common"
---
> More information: <https://nano-editor.org>.

- Open a new file in nano:

```bash
nano
```

- Open a specific file:

```bash
nano path/to/file
```

- Open a specific file, positioning the cursor at the specified line and column:

```bash
nano +line,column path/to/file
```

- Open a specific file and enable soft wrapping:

```bash
nano --softwrap path/to/file
```

- Open a specific file and indent new lines to the previous lines' indentation:

```bash
nano --autoindent path/to/file
```

- Open nano and create a backup file (`file~`) when saving edits:

```bash
nano --backup path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | nano: refresh (#6235) | 2021-07-28T16:10:07 | [057a416929bd](https://github.com/tldr-pages/tldr/commit/057a416929bd8f572e144f11a01281eebd64a832)
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | nano: add new command for backup (#4397) | 2020-10-05T15:56:27 | [33079e3240b3](https://github.com/tldr-pages/tldr/commit/33079e3240b3e19727e9bf80673a7b9f8632d7ba)
[Nir Elbaz](mailto:nire0510@gmail.com) | nano: add example and reword page (#3771) | 2020-01-29T16:16:44 | [545a95dd9082](https://github.com/tldr-pages/tldr/commit/545a95dd90826534775fb4613c20a01758c168b0)
[pxgamer](mailto:owzie123@gmail.com) | nano: add link to homepage | 2019-06-04T21:29:40 | [a1ed7f5f3c47](https://github.com/tldr-pages/tldr/commit/a1ed7f5f3c473dc8613b816a3c9a5b46469c8da4)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | nano: linting | 2016-01-19T14:11:20 | [b185c58fa8fa](https://github.com/tldr-pages/tldr/commit/b185c58fa8fa565071f0acc0403383fa08ab9b61)
[Jose Lemus](mailto:jlemus@bu.edu) | nano: Remove keybindings help. Add some command line options | 2015-12-31T01:04:05 | [45ff694e1394](https://github.com/tldr-pages/tldr/commit/45ff694e13946995da68d1d75233a2ce8c8cf8f2)
[Jose Lemus](mailto:jlemus@bu.edu) | Remove keybindings help. Add some command line options | 2015-12-31T01:01:15 | [7a75297ca538](https://github.com/tldr-pages/tldr/commit/7a75297ca538cb4deecdb155303b6c1f7212971e)
[Jose Lemus](mailto:jlemus@bu.edu) | nano: started tldr for nano | 2015-12-30T20:31:49 | [670db7af07d8](https://github.com/tldr-pages/tldr/commit/670db7af07d8a4f497295993921629914b14e826)

