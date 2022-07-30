---
author: ['Waldir Pimenta', 'Daniel Bayley', 'meowmeowcat', 'Emily Grace Seville', 'bl-ue']
date: 1644837703
title: "osascript"
description: "osascript, Run AppleScript or JavaScript for Automation (JXA) from the command-line."
categories: "osx"
---
> More information: <https://ss64.com/osx/osascript.html>.

- Run an AppleScript command:

```bash
osascript -e "say 'Hello world'"
```

- Run multiple AppleScript commands:

```bash
osascript -e "say 'Hello'" -e "say 'world'"
```

- Run a compiled (`*.scpt`), bundled (`*.scptd`), or plaintext (`*.applescript`) AppleScript file:

```bash
osascript path/to/apple.scpt
```

- Get the bundle identifier of an application (useful for `open -b`):

```bash
osascript -e 'id of app "Application"'
```

- Run a JavaScript command:

```bash
osascript -l JavaScript -e "console.log('Hello world');"
```

- Run a JavaScript file:

```bash
osascript -l JavaScript path/to/script.js
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osascript, xattr, pmset, say, screencapture: add link (#7368) | 2021-11-02T14:02:04 | [b85bc433fb19](https://github.com/tldr-pages/tldr/commit/b85bc433fb1916e6fd9b053f9db24284d11fc4e6)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | osascript: clarify extensions for script files | 2017-09-06T05:36:10 | [b924e34501b7](https://github.com/tldr-pages/tldr/commit/b924e34501b725c0ec6ef5d14e6a36c42003b04a)
[Daniel Bayley](mailto:daniel.bayley@me.com) | Update run AppleScript example | 2017-08-12T18:34:54 | [ba2530f42534](https://github.com/tldr-pages/tldr/commit/ba2530f42534f3b164662cdec12c3a76bf7c2166)
[Daniel Bayley](mailto:daniel.bayley@me.com) | osascript: add page Also referred to from the open page. | 2017-08-05T20:26:44 | [bc2549212113](https://github.com/tldr-pages/tldr/commit/bc2549212113219833d88ce74ade7e2eb5f9e309)

