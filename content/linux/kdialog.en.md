---
author: ['marchersimon']
date: 1651612165
title: "kdialog"
description: "kdialog, Show KDE dialog boxes from within shell scripts."
categories: "linux"
---
> More information: <https://develop.kde.org/deploy/kdialog/>.

- Open a dialog box displaying a specific message:

```bash
kdialog --msgbox "message" "optional_detailed_message"
```

- Open a question dialog with a `yes` and `no` button, returning `0` and `1`, respectively:

```bash
kdialog --yesno "message"
```

- Open a warning dialog with a `yes`, `no`, and `cancel` button, returning `0`, `1`, or `2` respectively:

```bash
kdialog --warningyesnocancel "message"
```

- Open an input dialog box and print the input to stdout when `OK` is pressed:

```bash
kdialog --inputbox "message" "optional_default_text"
```

- Open a dialog to prompt for a specific password and print it to stdout:

```bash
kdialog --password "message"
```

- Open a dialog containing a specific dropdown menu and print the selected item to stdout:

```bash
kdialog --combobx "message" "item1" "item2" "..."
```

- Open a file chooser dialog and print the selected file's path to stdout:

```bash
kdialog --getopenfilename
```

- Open a progressbar dialog and print a DBUS reference for communication to stdout:

```bash
kdialog --progressbar "message"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | kdialog: add page (#8071) | 2022-05-03T23:09:25 | [2eefbce0c105](https://github.com/tldr-pages/tldr/commit/2eefbce0c105224f0970f1529fa85978d1d1998c)

