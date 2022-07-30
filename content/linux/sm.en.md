---
author: ['Waldir Pimenta', 'Sacha Bron', 'Marco Bonelli']
date: 1559564381
title: "sm"
description: "sm, Displays a short message fullscreen."
categories: "linux"
---
> More information: <https://github.com/nomeata/screen-message>.

- Display a message in full-screen:

```bash
sm "Hello World!"
```

- Display a message with inverted colors:

```bash
sm -i "Hello World!"
```

- Display a message with a custom foreground color:

```bash
sm -f blue "Hello World!"
```

- Display a message with a custom background color:

```bash
sm -b #008888 "Hello World!"
```

- Display a message rotated 3 times (in steps of 90 degrees, counterclockwise):

```bash
sm -r 3 "Hello World!"
```

- Display a message using the output from another command:

```bash
echo "Hello World!" | sm -
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sm: add homepage, quote strings, improve descriptions (#3015) | 2019-05-12T16:33:55 | [f3e7ede68fb1](https://github.com/tldr-pages/tldr/commit/f3e7ede68fb113b18240e8776a73243636c456b7)
[Sacha Bron](mailto:BinaryBrain@users.noreply.github.com) | sm: add page (#2529) | 2018-11-02T13:55:25 | [960a3676bc72](https://github.com/tldr-pages/tldr/commit/960a3676bc727696eacbf0327fda7baad4d7b1a6)

