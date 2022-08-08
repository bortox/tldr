---
author: ['K.B.Dharun Krishna']
date: 1659905070
title: "powershell"
description: "powershell, குறிப்பாக கணினி நிர்வாகத்திற்காக வடிவமைக்கப்பட்ட கட்டளை வரி ஷெல் மற்றும் ஸ்கிரிப்டிங் மொழி."
categories: "common"
---
> மேலும் பார்க்கவும்: `pwsh`.

> மேலும் விவரத்திற்கு: <https://docs.microsoft.com/windows-server/administration/windows-commands/powershell>.

- ஊடாடும் ஷெல் அமர்வைத் தொடங்கவும்:

```bash
powershell
```

- தொடக்க கட்டமைப்புகளை ஏற்றாமல் ஊடாடும் ஷெல் அமர்வைத் தொடங்கவும்:

```bash
powershell -NoProfile
```

- குறிப்பிட்ட கட்டளைகளை இயக்கவும்:

```bash
powershell -Command "echo 'பவர்ஷெல் செயல்படுத்தப்படுகிறது'"
```

- ஒரு குறிப்பிட்ட ஸ்கிரிப்டை இயக்கவும்:

```bash
powershell -File பாதை/டு/ஸ்கிரிப்ட்.ps1
```

- பவர்ஷெல்லின் குறிப்பிட்ட பதிப்பைக் கொண்டு அமர்வைத் தொடங்கவும்:

```bash
powershell -Version பதிப்பு
```

- தொடக்க கட்டளைகளை இயக்கிய பிறகு ஷெல் வெளியேறுவதைத் தடுக்கவும்:

```bash
powershell -NoExit
```

- பவர்ஷெல்லுக்கு அனுப்பப்பட்ட தரவின் வடிவமைப்பை விவரிக்கவும்:

```bash
powershell -InputFormat Text|XML
```

- பவர்ஷெல்லின் வெளியீடு எவ்வாறு வடிவமைக்கப்படுகிறது என்பதைத் தீர்மானிக்கவும்:

```bash
powershell -OutputFormat Text|XML
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | pages.ta/*: fix more information Tamil translation (#8320) | 2022-08-07T22:44:30 | [e2a742ca82e2](https://github.com/tldr-pages/tldr/commit/e2a742ca82e2889a2d605962a45196e64b7579e4)
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | powershell: add Tamil translation (#8317) | 2022-08-07T17:51:11 | [ef1a2c557bd7](https://github.com/tldr-pages/tldr/commit/ef1a2c557bd7c4f86e8ad0d71a882db5e091abc9)

