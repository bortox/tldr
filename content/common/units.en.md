---
author: ['marchersimon']
date: 1617187653
title: "units, TLDR Pages"
description: "units, Provide the conversion between two units of measure."
categories: "common"
---
> More information: <https://www.gnu.org/software/units/>.

- Run in interactive mode:

```bash
units
```

- List all units containing a specific string in interactive mode:

```bash
search string
```

- Show the conversion between two simple units:

```bash
units quarts tablespoons
```

- Convert between units with quantities:

```bash
units "15 pounds" kilograms
```

- Show the conversion between two compound units:

```bash
units "meters / second" "inches / hour"
```

- Show the conversion between units with different dimensions:

```bash
units "acres" "ft^2"
```

- Show the conversion of byte multipliers:

```bash
units "15 megabytes" bytes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | units: move to common directory (#5647) | 2021-03-31T12:47:33 | [2bbd7bbd9f7f](https://github.com/tldr-pages/tldr/commit/2bbd7bbd9f7f8dd56b1dc6187674dc71fa0c913f)

