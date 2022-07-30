---
author: ['derNiklaas', 'Starbeamrainbowlabs']
date: 1633404950
title: "whiptail"
description: "whiptail, Display text-based dialog boxes from shell scripts."
categories: "linux"
---
> More information: <https://manned.org/whiptail>.

- Display a simple message:

```bash
whiptail --title "title" --msgbox "message" height_in_chars width_in_chars
```

- Display a boolean choice, returning the result through the exit code:

```bash
whiptail --title "title" --yesno "message" height_in_chars width_in_chars
```

- Customise the text on the yes / no buttons:

```bash
whiptail --title "title" --yes-button "text" --no-button "text" --yesno "message" height_in_chars width_in_chars
```

- Display a text input box:

```bash
result_variable_name="$(whiptail --title "title" --inputbox "message" height_in_chars width_in_chars default_text 3>&1 1>&2 2>&3)"
```

- Display a password input box:

```bash
result_variable_name="$(whiptail --title "title" --passwordbox "message" height_in_chars width_in_chars 3>&1 1>&2 2>&3)"
```

- Display a multiple-choice menu:

```bash
result_variable_name=$(whiptail --title "title" --menu "message" height_in_chars width_in_chars menu_display_height "value_1" "display_text_1" "value_n" "display_text_n" ..... 3>&1 1>&2 2>&3)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | whiptail: add page (#2820) | 2019-03-07T10:50:16 | [3aef0112fca7](https://github.com/tldr-pages/tldr/commit/3aef0112fca76e0033807f8feda04345e3e31df7)

