---
author: ['Waldir Pimenta', 'Ben Scattergood', 'Zlatan Vasović', 'mxmxyz', 'Starbeamrainbowlabs']
date: 1577490836
title: "firefox, TLDR Pages"
description: "firefox, A free and open source web browser."
categories: "common"
---
> More information: <https://developer.mozilla.org/en-US/docs/Mozilla/Command_Line_Options>.

- Launch Firefox and open a web page:

```bash
firefox https://www.duckduckgo.com
```

- Open a new window:

```bash
firefox --new-window https://www.duckduckgo.com
```

- Open a private (incognito) window:

```bash
firefox --private-window
```

- Search for "wikipedia" using the default search engine:

```bash
firefox --search "wikipedia"
```

- Launch Firefox in safe mode, with all extensions disabled:

```bash
firefox --safe-mode
```

- Take a screenshot of a web page in headless mode:

```bash
firefox --headless --screenshot path/to/output_file.png https://example.com/
```

- Use a specific profile to allow multiple separate instances of Firefox to run at once:

```bash
firefox --profile path/to/directory https://example.com/
```

- Set Firefox as the default browser:

```bash
firefox --setDefaultBrowser
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | Remove new profile command | 2019-12-28T00:53:56 | [3f48086d34b2](https://github.com/tldr-pages/tldr/commit/3f48086d34b21c6d347c740835d442f76dfccb83)
[Ben Scattergood](mailto:benscattergood@gmail.com) | Firefox: Suggested changes New instance flag removed but profile flag re-added | 2019-12-28T00:53:56 | [45247399e2c9](https://github.com/tldr-pages/tldr/commit/45247399e2c908301f8f66caa002fc7d1df5552d)
[Ben Scattergood](mailto:benscattergood@gmail.com) | Firefox: suggested changes grammatical change for default browser flag Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2019-12-28T00:53:56 | [4434c26c9854](https://github.com/tldr-pages/tldr/commit/4434c26c9854d9451fd506a185bf4872f0d2b043)
[Ben Scattergood](mailto:benscattergood@gmail.com) | firefox: remove --new-instance flag | 2019-12-28T00:53:56 | [9c3bb17ba388](https://github.com/tldr-pages/tldr/commit/9c3bb17ba38816c5e173a71100079333bfe65222)
[Ben Scattergood](mailto:benscattergood@gmail.com) | Added missing backtick | 2019-12-28T00:53:56 | [a7a6d84942b3](https://github.com/tldr-pages/tldr/commit/a7a6d84942b3f8e64a1f563fa3e8748198422cd3)
[Ben Scattergood](mailto:benscattergood@gmail.com) | firefox: add extra flag options also added note that profile selection is not available on windows | 2019-12-28T00:53:56 | [944b10aba4af](https://github.com/tldr-pages/tldr/commit/944b10aba4af44e89466ad60223618521b39c4fc)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | firefox: improve example descriptions (#3276) Also fix the main description to conform to the style guide. | 2019-09-21T22:39:37 | [b7926ee5db63](https://github.com/tldr-pages/tldr/commit/b7926ee5db639855e0b7dc4a019b22a95d0dc1b7)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | firefox: expand & update syntax to version 60+ (#3263) | 2019-09-13T20:17:51 | [6356845d956c](https://github.com/tldr-pages/tldr/commit/6356845d956cd097955a96db8d056d2da9574781)
[mxmxyz](mailto:45631125+mxmxyz@users.noreply.github.com) | firefox: add page (#3261) | 2019-09-11T16:27:40 | [813291581fee](https://github.com/tldr-pages/tldr/commit/813291581feece1ed9e800992add830afb85daeb)

