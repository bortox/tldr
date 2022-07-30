---
author: ['Matan Rubin', 'pxgamer']
date: 1559328460
title: "protoc"
description: "protoc, Parse Google Protobuf `.proto` files and generate output in the specified language."
categories: "common"
---
> More information: <https://developers.google.com/protocol-buffers>.

- Generate Python code from a `.proto` file:

```bash
protoc --python_out=path/to/output_directory input_file.proto
```

- Generate Java code from a `.proto` file that imports other `.proto` files:

```bash
protoc --java_out=path/to/output_directory --proto_path=path/to/import_search_path input_file.proto
```

- Generate code for multiple languages:

```bash
protoc --csharp_out=path/to/c#_output_directory --js_out=path/to/js_output_directory input_file.proto
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | protoc: add link to homepage | 2019-05-31T20:47:40 | [83bf89932c0e](https://github.com/tldr-pages/tldr/commit/83bf89932c0e5bf066a53916d2f49bc57c78673a)
[Matan Rubin](mailto:matanaloni@gmail.com) | protoc: add page for Google Protobuf (#1698) | 2017-11-30T16:00:13 | [43faabe02747](https://github.com/tldr-pages/tldr/commit/43faabe027477955bb49c3db8af94f0da33f2b7c)

