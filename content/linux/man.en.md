---
author: ['Mia Combeau', 'kai']
date: 1662474547
title: "man"
description: "man, Format and display manual pages."
categories: "linux"
---
> More information: <https://www.man7.org/linux/man-pages/man1/man.1.html>.

- Display the man page for a command:

```bash
man command
```

- Display the man page for a command from section 7:

```bash
man 7 command
```

- List all available sections for a command:

```bash
man --whatis command
```

- Display the path searched for manpages:

```bash
man --path
```

- Display the location of a manpage rather than the manpage itself:

```bash
man --where command
```

- Display the man page using a specific locale:

```bash
man --locale=locale command
```

- Search for manpages containing a search string:

```bash
man --apropos "search_string"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mia Combeau](mailto:52008667+mcombeau@users.noreply.github.com) | man: fix locale option example (#8465) | 2022-09-06T16:29:07 | [f855dd1b1f03](https://github.com/tldr-pages/tldr/commit/f855dd1b1f035d52551468d7de10603bae786ad2)
[kai](mailto:gmdezreal@gmail.com) | man: use long options in examples (#8216) * man: use long options in examples * man: move long options to /linux/ | 2022-07-19T04:15:19 | [31325d9bd8bd](https://github.com/tldr-pages/tldr/commit/31325d9bd8bd0fbed7cb9d4d2cde6546d8d8f8ab)

