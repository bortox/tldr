---
author: ['K.B.Dharun Krishna']
date: 1660307402
title: "toolbox create"
description: "toolbox create, புதிய `toolbox` கொள்கலனை உருவாக்கவும்."
categories: "linux"
---
> மேலும் விவரத்திற்கு: <https://manned.org/toolbox-create.1>.

- ஒரு குறிப்பிட்ட விநியோகத்திற்காக `toolbox` கொள்கலனை உருவாக்கவும்:

```bash
toolbox create --distro விநியோகம்
```

- தற்போதைய விநியோகத்தின் குறிப்பிட்ட வெளியீட்டிற்கு `toolbox` கொள்கலனை உருவாக்கவும்:

```bash
toolbox create --release வெளியீடு
```

- தனிப்பயன் படத்துடன் `toolbox` கொள்கலனை உருவாக்கவும்:

```bash
toolbox create --image பெயர்
```

- தனிப்பயன் ஃபெடோரா படத்திலிருந்து `toolbox` கொள்கலனை உருவாக்கவும்:

```bash
toolbox create --image registry.fedoraproject.org/fedora-toolbox:36
```

- ஃபெடோரா 36க்கான இயல்புநிலை படத்தைப் பயன்படுத்தி `toolbox` கொள்கலனை உருவாக்கவும்:

```bash
toolbox create --distro fedora --release f36
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | toolbox*: add Tamil translation (#8338) | 2022-08-12T14:30:02 | [9eed96620776](https://github.com/tldr-pages/tldr/commit/9eed96620776be57b639c8afe583e620ba77b331)

