---
author: ['Mateusz Soszyński', 'Christopher Kümmel', 'pxgamer', 'ev-john', 'Martin L. Jensen', 'Balázs Úr']
date: 1607721947
title: "flutter, TLDR Pages"
description: "flutter, Google's free, open source, and cross-platform mobile app SDK."
categories: "common"
---
> More information: <https://github.com/flutter/flutter/wiki/The-flutter-tool>.

- Display help about a specific command:

```bash
flutter help command
```

- Check if all external tools are correctly installed:

```bash
flutter doctor
```

- List or change Flutter channel:

```bash
flutter channel stable|beta|dev|master
```

- Run Flutter on all started emulators and connected devices:

```bash
flutter run -d all
```

- Download all packages specified in `pubspec.yaml`:

```bash
flutter pub get
```

- Run tests in a terminal from the root of the project:

```bash
flutter test test/example_test.dart
```

- Build a release APK targeting most modern smartphones:

```bash
flutter build apk --target-platform android-arm,android-arm64
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mateusz Soszyński](mailto:mateusz.soszynski@tuta.io) | flutter: fix typo (#5020) Platforms need to be divided only by `,` not space | 2020-12-11T22:25:47 | [e5a6af0299b0](https://github.com/tldr-pages/tldr/commit/e5a6af0299b00a9953caaca2acaff40d163a6171)
[Mateusz Soszyński](mailto:mateusz.soszynski@tuta.io) | flutter: remove useless examples and add release APK (#4853) | 2020-10-28T19:03:05 | [017e0ced2e04](https://github.com/tldr-pages/tldr/commit/017e0ced2e04c9ccd8ed479720a0bf9a5a3721b2)
[ev-john](mailto:56849582+ev-john@users.noreply.github.com) | flutter: add test command (#4625) | 2020-10-12T23:39:07 | [00c6d6ca2ccf](https://github.com/tldr-pages/tldr/commit/00c6d6ca2ccf8d27ff62a748bbbb87857c42b55a)
[Martin L. Jensen](mailto:martinloesethjensen@gmail.com) | flutter: added suggestion with select options Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-09-09T02:09:07 | [75fcfdab4ee4](https://github.com/tldr-pages/tldr/commit/75fcfdab4ee46aa658e66e10a3e5c2e63c58e816)
[Martin L. Jensen](mailto:martinloesethjensen@gmail.com) | flutter: fix space after colon | 2020-09-09T02:09:07 | [6ed0deee25ab](https://github.com/tldr-pages/tldr/commit/6ed0deee25ab604971ea739cf834bfaf73bc3261)
[Martin L. Jensen](mailto:martinloesethjensen@gmail.com) | flutter: add run example Example of running flutter on all emulators and devices | 2020-09-09T02:09:07 | [600df8ce48d2](https://github.com/tldr-pages/tldr/commit/600df8ce48d2ba9fea0b501a4d2f88edfbc890c6)
[Martin L. Jensen](mailto:martinloesethjensen@gmail.com) | flutter: fix typo | 2020-09-09T02:09:07 | [77763027bd55](https://github.com/tldr-pages/tldr/commit/77763027bd550e34b6898f542d360cbb9f71caba)
[Martin L. Jensen](mailto:martinloesethjensen@gmail.com) | flutter: add channel example | 2020-09-09T02:09:07 | [6a0cd5f7708d](https://github.com/tldr-pages/tldr/commit/6a0cd5f7708d421654f0313e3e1303dfdc6a01fe)
[pxgamer](mailto:owzie123@gmail.com) | flutter: add link to homepage | 2019-06-07T23:58:59 | [0c64e6647869](https://github.com/tldr-pages/tldr/commit/0c64e66478690e6a34fadadf2e75f53e82c5f760)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: change Unicode characters to ASCII (#2802) Change Unicode characters to ASCII: - non-breaking spaces (\xc2\xa0) to [...] | 2019-02-25T00:56:24 | [6956cd5348e4](https://github.com/tldr-pages/tldr/commit/6956cd5348e4f87db1586a68ab299e46f7384b63)
[Christopher Kümmel](mailto:kuemmel.christopher@gmail.com) | flutter: add page (#2220) | 2018-07-26T00:47:24 | [d1280cfc5c04](https://github.com/tldr-pages/tldr/commit/d1280cfc5c04613fde9ade770d5751a2887eebaf)

