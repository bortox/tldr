---
author: ['Axel Navarro']
date: 1647197264
title: "svgr, TLDR Pages"
description: "svgr, Transform SVGs into React components."
categories: "common"
---
> More information: <https://react-svgr.com>.

- Transform a SVG file into a React component to stdout:

```bash
svgr -- path/to/file.svg
```

- Transform a SVG file into a React component using TypeScript to stdout:

```bash
svgr --typescript -- path/to/file.svg
```

- Transform a SVG file into a React component using JSX transform to stdout:

```bash
svgr --jsx-runtime automatic -- path/to/file.svg
```

- Transform all SVG files from a directory to React components into a specific directory:

```bash
svgr --out-dir path/to/output_directory path/to/input_directory
```

- Transform all SVG files from a directory to React components into a specific directory skipping already transformed files:

```bash
svgr --out-dir path/to/output_directory --ignore-existing path/to/input_directory
```

- Transform all SVG files from a directory to React components into a specific directory using a specific case for filenames:

```bash
svgr --out-dir path/to/output_directory --filename-case camel|kebab|pascal path/to/input_directory
```

- Transform all SVG files from a directory to React components into a specific directory without generating an index file:

```bash
svgr --out-dir path/to/output_directory --no-index path/to/input_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | svgr: add page (#7882) | 2022-03-13T19:47:44 | [c85155ec0b0d](https://github.com/tldr-pages/tldr/commit/c85155ec0b0df7535edc597409bd4ab5365e9479)

