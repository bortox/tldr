---
author: ['pixel', 'Zlatan Vasović', 'pxgamer', 'Waldir Pimenta']
date: 1631455407
title: "julia, TLDR Pages"
description: "julia, A high-level, high-performance dynamic programming language for technical computing."
categories: "common"
---
> More information: <https://docs.julialang.org/en/v1/manual/getting-started/>.

- Start a REPL (interactive shell):

```bash
julia
```

- Execute a Julia program and exit:

```bash
julia program.jl
```

- Execute a Julia program that takes arguments:

```bash
julia program.jl arguments
```

- Evaluate a string containing Julia code:

```bash
julia -e 'julia_code'
```

- Evaluate a string of Julia code, passing arguments to it:

```bash
julia -e 'for x in ARGS; println(x); end' arguments
```

- Evaluate an expression and print the result:

```bash
julia -E '(1 - cos(pi/4))/2'
```

- Start Julia in parallel mode, using N worker processes:

```bash
julia -p N
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | pages/common/*.md: REPL Normalization (#6471) | 2021-09-12T16:03:27 | [882781e41019](https://github.com/tldr-pages/tldr/commit/882781e41019543fd716442e62faa1fb02d474b9)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | julia: add -E example, fix link (#4062) | 2020-05-25T17:43:07 | [b93d22d70741](https://github.com/tldr-pages/tldr/commit/b93d22d7074105ecdf71ca54cec231dc9b91c8a8)
[pxgamer](mailto:owzie123@gmail.com) | julia: add link to homepage | 2019-06-06T04:42:48 | [2c4ae55bb648](https://github.com/tldr-pages/tldr/commit/2c4ae55bb648e36b370d75b6032a7189de6ece88)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | julia: add page (#1089) Based on the [man page](https://github.com/JuliaLang/julia/blob/master/doc/man/julia.1), and on the [Getting [...] | 2016-10-13T17:50:43 | [316d36256e2d](https://github.com/tldr-pages/tldr/commit/316d36256e2d2a09f0ad60a3416b6c0d8cd016ff)

