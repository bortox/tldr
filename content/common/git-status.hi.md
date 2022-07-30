---
author: ['9tykeshav', 'lincc']
date: 1643487459
title: "git status"
description: "git status, गिट रिपॉजिटरी में फाइलों में बदलाव दिखाएं।"
categories: "common"
---
> उन पथों को प्रदर्शित करता है जिनमें अनुक्रमणिका फ़ाइल और वर्तमान हेड कमिट के बीच अंतर होता है।

> अधिक जानकारी: <https://git-scm.com/docs/git-status>।

- बदली हुई फ़ाइलें दिखाएं जो अभी तक कमिट के लिए नहीं जोड़ी गई हैं:

```bash
git status
```

- शॉर्ट-फॉर्मेट में आउटपुट दें:

```bash
git status -s
```

- आउटपुट में ट्रैक न की गई फ़ाइलें न दिखाएं:

```bash
git status --untracked-files=no
```

- [b]शाखा की जानकारी के साथ [s]लघु प्रारूप में आउटपुट दिखाएं:

```bash
git status -sb
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[9tykeshav](mailto:57292513+9tykeshav@users.noreply.github.com) | git-status: add Hindi translation (#6677) | 2021-10-07T19:16:38 | [90b9dc96f768](https://github.com/tldr-pages/tldr/commit/90b9dc96f7683a7bb8286917cc0ec025df0b3752)

