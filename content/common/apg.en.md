---
author: ['michaelAndersonCampingWorld', 'marchersimon']
date: 1618756407
title: "apg, TLDR Pages"
description: "apg, Creates arbitrarily complex random passwords."
categories: "common"
---
> More information: <https://manned.org/apg>.

- Create random passwords (default password length is 8):

```bash
apg
```

- Create a password with at least 1 symbol (S), 1 number (N), 1 uppercase (C), 1 lowercase (L):

```bash
apg -M SNCL
```

- Create a password with 16 characters:

```bash
apg -m 16
```

- Create a password with maximum length of 16:

```bash
apg -x 16
```

- Create a password that doesn't appear in a dictionary (the dictionary file has to be provided):

```bash
apg -r dictionary_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> Co-authored-by: bl-ue <54780737+bl- [...] | 2021-04-18T16:33:27 | [a8cbf084db1c](https://github.com/tldr-pages/tldr/commit/a8cbf084db1c27995da74db5833681eaea87dbfb)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: edit link | 2021-04-18T16:33:27 | [ec6a3682f0fe](https://github.com/tldr-pages/tldr/commit/ec6a3682f0feaea05c28b65ddac54d395b32a284)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: add link | 2021-04-18T16:33:27 | [d5cbcd6fbca3](https://github.com/tldr-pages/tldr/commit/d5cbcd6fbca3201f690a82f177faf6679349e803)
[michaelAndersonCampingWorld](mailto:michael.anderson@campingworld.com) | apg: add page (#1013) * add page with examples for apg (advanced password generator) * edits per code review * spread the examples [...] | 2016-08-26T13:07:09 | [35635d7afb78](https://github.com/tldr-pages/tldr/commit/35635d7afb78b83b850e56cd42f44e301fbb6437)

