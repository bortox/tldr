---
author: ['Iain']
date: 1607083645
title: "exenv"
description: "exenv, A tool to easily install Elixir versions and manage application environments."
categories: "common"
---
> More information: <https://github.com/exenv/exenv>.

- Display a list of installed versions:

```bash
exenv versions
```

- Use a specific version of Elixir across the whole system:

```bash
exenv global version
```

- Use a specific version of Elixir for the current application/project directory:

```bash
exenv local version
```

- Show the currently selected Elixir version:

```bash
exenv version
```

- Install a version of Elixir (requires `elixir-build` plugin <https://github.com/mururu/elixir-build>):

```bash
exenv install version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Iain](mailto:irwalker@users.noreply.github.com) | exenv: add page (#4992) | 2020-12-04T13:07:25 | [395351ad7e45](https://github.com/tldr-pages/tldr/commit/395351ad7e455ddc1550f8f62503513c117db0bc)

