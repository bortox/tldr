---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "cmd, TLDR Pages"
description: "cmd, விண்டோஸ் கட்டளை மொழிபெயர்ப்பாளர்."
categories: "windows"
---
> மேலும் விவரத்திற்கு: <https://docs.microsoft.com/windows-server/administration/windows-commands/cmd>.

- கட்டளை மொழிபெயர்ப்பாளரின் புதிய நிகழ்வைத் தொடங்கவும்:

```bash
cmd
```

- குறிப்பிட்ட கட்டளையை இயக்கவும், பின்னர் வெளியேறவும்:

```bash
cmd /c "கட்டளை"
```

- குறிப்பிட்ட கட்டளையை இயக்கவும், பின்னர் ஒரு ஊடாடும் ஷெல்லை உள்ளிடவும்:

```bash
cmd /k "கட்டளை"
```

- கட்டளை வெளியீட்டில் `echo` இன் பயன்பாட்டை முடக்கு:

```bash
cmd /q
```

- கட்டளை நீட்டிப்புகளை இயக்கவும் அல்லது முடக்கவும்:

```bash
cmd /e:on|off
```

- கோப்பு அல்லது கோப்பக தானியங்குநிரலை இயக்கவும் அல்லது முடக்கவும்:

```bash
cmd /f:on|off
```

- சூழல் மாறி விரிவாக்கத்தை இயக்கவும் அல்லது முடக்கவும்:

```bash
cmd /v:on|off
```

- யூனிகோட் குறியாக்கத்தைப் பயன்படுத்த வெளியீட்டை கட்டாயப்படுத்தவும்:

```bash
cmd /u
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | cd, cls, cmd: add Tamil translation (#4631) Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:09:52 | [2a2786cf0b56](https://github.com/tldr-pages/tldr/commit/2a2786cf0b566728c7d4b60cda1aac3f438d0c74)

