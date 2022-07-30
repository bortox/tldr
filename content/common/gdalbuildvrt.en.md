---
author: ['RobinKohrs', 'bl-ue', 'Seth Falco']
date: 1656325392
title: "gdalbuildvrt"
description: "gdalbuildvrt, Build Virtual Datasets from a list of existing datasets."
categories: "common"
---
> More information: <https://gdal.org/programs/gdalbuildvrt.html>.

- Make a virtual mosaic from all TIFF files contained in a directory:

```bash
gdalbuildvrt path/to/output.vrt path/to/input_directory/*.tif
```

- Make a virtual mosaic from files whose name is specified in a text file:

```bash
gdalbuildvrt -input_file_list path/to/list.txt path/to/output.vrt
```

- Make an RGB virtual mosaic from 3 single-band input files:

```bash
gdalbuildvrt -separate path/to/rgb.vrt path/to/red.tif path/to/green.tif path/to/blue.tif
```

- Make a virtual mosaic with blue background color (RGB: 0 0 255):

```bash
gdalbuildvrt -hidenodata -vrtnodata "0 0 255" path/to/output.vrt path/to/input_directory/*.tif
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[RobinKohrs](mailto:48288925+RobinKohrs@users.noreply.github.com) | gdalbuildvrt: add page (#4941) | 2020-11-10T20:02:27 | [d9df7a2238a8](https://github.com/tldr-pages/tldr/commit/d9df7a2238a8c38c930a2f00bb4c325d33b4ca78)

