---
author: ['K.B.Dharun Krishna']
date: 1661719131
title: "asciiart"
description: "asciiart, படங்களை ASCII ஆக மாற்றவும்."
categories: "linux"
---
> மேலும் விவரத்திற்கு: <https://github.com/nodanaonlyzuul/asciiart>.

- ஒரு கோப்பிலிருந்து ஒரு படத்தைப் படித்து ASCII இல் அச்சிடவும்:

```bash
asciiart பாதை/டு/படம்.jpg
```

- URL இலிருந்து ஒரு படத்தைப் படித்து, ASCII இல் அச்சிடவும்:

```bash
asciiart www.example.com/image.jpg
```

- வெளியீட்டு அகலத்தைத் தேர்வு செய்யவும் (இயல்புநிலை 100):

```bash
asciiart --width 50 பாதை/டு/படம்.jpg
```

- ASCII வெளியீட்டை வண்ணமயமாக்கவும்:

```bash
asciiart --color பாதை/டு/படம்.jpg
```

- வெளியீட்டு வடிவமைப்பைத் தேர்வு செய்யவும் (இயல்புநிலை வடிவம் உரை):

```bash
asciiart --format text|html பாதை/டு/படம்.jpg
```

- எழுத்து வரைபடத்தைத் தலைகீழாக மாற்றவும்:

```bash
asciiart --invert-chars பாதை/டு/படம்.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | ascii, asciiart: add Tamil translation (#8415) | 2022-08-28T22:38:51 | [8b86e57401a5](https://github.com/tldr-pages/tldr/commit/8b86e57401a59805075c0b3aed1ad1ecd5949ca0)

