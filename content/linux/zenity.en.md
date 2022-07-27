---
author: ['Thomas Barusseau', 'derNiklaas', 'bl-ue']
date: 1633320039
title: "zenity, TLDR Pages"
description: "zenity, Display dialogs from the command-line/shell scripts."
categories: "linux"
---
> Return user-inserted values or 1 if error.

> More information: <https://manned.org/zenity>.

- Display the default question dialog:

```bash
zenity --question
```

- Display an info dialog displaying the text "Hello!":

```bash
zenity --info --text="Hello!"
```

- Display a name/password form and output the data separated by ";":

```bash
zenity --forms --add-entry="Name" --add-password="Password" --separator=";"
```

- Display a file selection form in which the user can only select directories:

```bash
zenity --file-selection --directory
```

- Display a progress bar which updates its message every second and show a progress percent:

```bash
(echo "#1"; sleep 1; echo "50"; echo "#2"; sleep 1; echo "100") | zenity --progress
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | zenity, zgrep, zramctl: add more information link (#6758) | 2021-10-04T06:00:39 | [c05f245fd530](https://github.com/tldr-pages/tldr/commit/c05f245fd530f6134b91568ae3d0181a74c6814b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Thomas Barusseau](mailto:baruss.thomas@gmail.com) | zenity: add page (#1687) | 2017-11-30T04:28:10 | [8571c78816bf](https://github.com/tldr-pages/tldr/commit/8571c78816bf5d9cb258ead69f5edcb20fa48523)

