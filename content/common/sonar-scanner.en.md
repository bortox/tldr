---
author: ['Karthikeyan Vaithilingam', 'bl-ue']
date: 1621541621
title: "sonar-scanner"
description: "sonar-scanner, SonarScanner is a generic scanner for SonarQube projects that do not use build tools such as Maven, Gradle, or Ant."
categories: "common"
---
> More information: <https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/>.

- Scan a project with configuration file in your project's root directory named `sonar-project.properties`:

```bash
sonar-scanner
```

- Scan a project using configuration file other than `sonar-project.properties`:

```bash
sonar-scanner -Dproject.settings=myproject.properties
```

- Print help information:

```bash
sonar-scanner -h
```

- Print debugging information:

```bash
sonar-scanner -X
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | sonar-scanner: add page (#4466) | 2020-10-05T13:17:34 | [77de61bb0645](https://github.com/tldr-pages/tldr/commit/77de61bb064570c30c72254dda5ce5916a2ca9a1)

