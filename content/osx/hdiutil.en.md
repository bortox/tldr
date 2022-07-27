---
author: ['Waldir Pimenta', 'Diogo Pinela', 'Kyle']
date: 1629747204
title: "hdiutil, TLDR Pages"
description: "hdiutil, Utility to create and manage disk images."
categories: "osx"
---
> More information: <https://ss64.com/osx/hdiutil.html>.

- Mount an image:

```bash
hdiutil attach path/to/image_file
```

- Unmount an image:

```bash
hdiutil detach /Volumes/volume_name
```

- List mounted images:

```bash
hdiutil info
```

- Create an ISO image from the contents of a directory:

```bash
hdiutil makehybrid -o path/to/output_file path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | hdiutil: improve tokens (#3602) | 2019-11-22T16:03:55 | [93420c3529bf](https://github.com/tldr-pages/tldr/commit/93420c3529bf111d5c9e78ac2ecef8c6bff69df1)
[Diogo Pinela](mailto:diogoid7400@gmail.com) | hdiutil: add page (#3389) | 2019-10-12T16:17:22 | [7e034ef54b91](https://github.com/tldr-pages/tldr/commit/7e034ef54b91bd4b66f4d1a79e33a9e768b16b00)

