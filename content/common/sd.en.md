---
author: ['Danny Mösch', 'Juri', 'Jesse Claven', 'marchersimon']
date: 1634444636
title: "sd"
description: "sd, Intuitive find & replace CLI."
categories: "common"
---
> More information: <https://github.com/chmln/sd>.

- Trim some whitespace using a regular expression:

```bash
echo 'lorem ipsum 23   ' | sd '\s+$' ''
```

- Replace words using capture groups:

```bash
echo 'cargo +nightly watch' | sd '(\w+)\s+\+(\w+)\s+(\w+)' 'cmd: $1, channel: $2, subcmd: $3'
```

- Find and replace in a file printing the result to stdout:

```bash
sd -p 'window.fetch' 'fetch' http.js
```

- Find and replace across a project changing each file in place:

```bash
sd 'from "react"' 'from "preact"' $(find . -type f)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | meshlabserver, nkf, obs, pax, pdfimages, pinky, pssh, s, sd, sendmail, sftp: add link (#6971) | 2021-10-17T06:23:56 | [977d4212d52c](https://github.com/tldr-pages/tldr/commit/977d4212d52c031de053f549d819b8b0e18ce184)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Danny Mösch](mailto:danny.moesch@icloud.com) | sd: Remove option -i in favour of option -p (#4209) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-07-21T22:50:14 | [ab00dce9de05](https://github.com/tldr-pages/tldr/commit/ab00dce9de05cc6f24dc501742e28cdfac17d3dd)
[Jesse Claven](mailto:jesse.claven@me.com) | sd: add page (#2810) | 2019-03-08T19:17:28 | [a30f616f9f12](https://github.com/tldr-pages/tldr/commit/a30f616f9f12bc6ff4a9bcdfd486a12cc6f6df39)

