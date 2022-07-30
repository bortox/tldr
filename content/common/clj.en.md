---
author: ['pixel', 'Diego B. Fernandez']
date: 1631455407
title: "clj"
description: "clj, Clojure tool to start a REPL or invoke a specific function with data."
categories: "common"
---
> All options can be defined in a `deps.edn` file.

> More information: <https://clojure.org/guides/deps_and_cli>.

- Start a REPL (interactive shell):

```bash
clj
```

- Execute a function:

```bash
clj -X namespace/function_name
```

- Run the main function of a specified namespace:

```bash
clj -M -m namespace args
```

- Prepare a project by resolving dependencies, downloading libraries, and making / caching classpaths:

```bash
clj -P
```

- Start an nREPL server with the CIDER middleware:

```bash
clj -Sdeps '{:deps {nrepl {:mvn/version "0.7.0"} cider/cider-nrepl {:mvn/version "0.25.2"}' -m nrepl.cmdline --middleware '["cider.nrepl/cider-middleware"]' --interactive
```

- Start a REPL for ClojureScript and open a web browser:

```bash
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version "1.10.758"}' --main cljs.main --repl
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | pages/common/*.md: REPL Normalization (#6471) | 2021-09-12T16:03:27 | [882781e41019](https://github.com/tldr-pages/tldr/commit/882781e41019543fd716442e62faa1fb02d474b9)
[Diego B. Fernandez](mailto:diegobfernandez@outlook.com) | clj: add page (#4980) * clj: add page * Update pages/common/clj.md * Update clj.md * Update clj.md * Apply suggestions from code [...] | 2020-12-23T14:59:36 | [f3e92ad0a441](https://github.com/tldr-pages/tldr/commit/f3e92ad0a4411f83f4eac2ed6e7181869e9fbdc6)

