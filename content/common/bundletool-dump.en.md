---
author: ['Axel Navarro']
date: 1613694157
title: "bundletool dump"
description: "bundletool dump, Command-line tool to manipulate Android Application Bundles."
categories: "common"
---
> More information: <https://developer.android.com/studio/command-line/bundletool>.

- Display the `AndroidManifest.xml` of the base module:

```bash
bundletool dump manifest --bundle=path/to/bundle.aab
```

- Display a specific value from the `AndroidManifest.xml` using XPath:

```bash
bundletool dump manifest --bundle=path/to/bundle.aab --xpath=/manifest/@android:versionCode
```

- Display the `AndroidManifest.xml` of a specific module:

```bash
bundletool dump manifest --bundle=path/to/bundle.aab --module=name
```

- Display all the resources in the application bundle:

```bash
bundletool dump resources --bundle=path/to/bundle.aab
```

- Display the configuration for a specific resource:

```bash
bundletool dump resources --bundle=path/to/bundle.aab --resource=type/name
```

- Display the configuration and values for a specific resource using the ID:

```bash
bundletool dump resources --bundle=path/to/bundle.aab --resource=0x7f0e013a --values
```

- Display the contents of the bundle configuration file:

```bash
bundletool dump config --bundle=path/to/bundle.aab
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | bundletool-dump: add page (#5266) | 2021-02-19T01:22:37 | [c28ff26226d3](https://github.com/tldr-pages/tldr/commit/c28ff26226d304c37dab6456e39c07e8062fc840)

