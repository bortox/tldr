---
author: ['Axel Navarro', 'marchersimon']
date: 1631521281
title: "bundletool"
description: "bundletool, Command-line tool to manipulate Android Application Bundles."
categories: "common"
---
> Some subcommands such as `bundletool validate` have their own usage documentation.

> More information: <https://developer.android.com/studio/command-line/bundletool>.

- Display help for a subcommand:

```bash
bundletool help subcommand
```

- Generate APKs from an application bundle (prompts for keystore password):

```bash
bundletool build-apks --bundle=path/to/bundle.aab --ks=path/to/key.keystore --ks-key-alias=key_alias --output=path/to/file.apks
```

- Generate APKs from an application bundle giving the keystore password:

```bash
bundletool build-apks --bundle=path/to/bundle.aab --ks=path/to/key.keystore --ks-key-alias=key_alias –ks-pass=pass:the_password --output=path/to/file.apks
```

- Generate APKs including only one single APK for universal usage:

```bash
bundletool build-apks --bundle=path/to/bundle.aab --mode=universal --ks=path/to/key.keystore --ks-key-alias=key_alias --output=path/to/file.apks
```

- Install the right combination of APKs to an emulator or device:

```bash
bundletool install-apks --apks=path/to/file.apks
```

- Estimate the download size of an application:

```bash
bundletool get-size total --apks=path/to/file.apks
```

- Generate a device specification JSON file for an emulator or device:

```bash
bundletool get-device-spec --output=path/to/file.json
```

- Verify a bundle and display detailed information about it:

```bash
bundletool validate --bundle=path/to/bundle.aab
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Axel Navarro](mailto:navarroaxel@gmail.com) | bundletool, bundletool-validate: add page (#5263) | 2021-03-13T01:04:37 | [3192ab066b8d](https://github.com/tldr-pages/tldr/commit/3192ab066b8d4ba0000ea17fe56127763c4e12d9)

