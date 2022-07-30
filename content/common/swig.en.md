---
author: ['pixel', 'bl-ue', 'Seth Falco', 'Albert']
date: 1643706393
title: "swig"
description: "swig, Generate bindings between C / C++ code and various high level languages such as JavaScript, Python, C#, and more."
categories: "common"
---
> It uses special .i or .swg files to generate the bindings (C/C++ with SWIG directives, then outputs a C/C++ file that contains all the wrapper code needed to build an extension module.

> More information: <http://www.swig.org>.

- Generate a binding between C++ and Python:

```bash
swig -c++ -python -o path/to/output_wrapper.cpp path/to/swig_file.i
```

- Generate a binding between C++ and Go:

```bash
swig -go -cgo -intgosize 64 -c++ path/to/swig_file.i
```

- Generate a binding between C and Java:

```bash
swig -java path/to/swig_file.i
```

- Generate a binding between C and Ruby and prefix the Ruby module with {{foo::bar::}}:

```bash
swig -ruby -prefix "foo::bar::" path/to/swig_file.i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | socat, sn, slimrb, swig: add more information link (#7733) | 2022-02-01T10:06:33 | [2396c6d791e9](https://github.com/tldr-pages/tldr/commit/2396c6d791e95702a3320ea3b13337f4a34998ea)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Albert](mailto:alufers@wp.pl) | swig: add page (#3951) | 2020-04-01T02:17:09 | [f13287de2ee0](https://github.com/tldr-pages/tldr/commit/f13287de2ee0615f1ac9dda92b080e032e2a5fe1)

