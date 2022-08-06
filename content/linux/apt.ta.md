---
author: ['K.B.Dharun Krishna']
date: 1659683329
title: "apt"
description: "apt, டெபியன் அடிப்படையிலான விநியோகங்களுக்கான தொகுப்பு மேலாண்மை பயன்பாடு."
categories: "linux"
---
> உபுண்டு பதிப்பு 16.04 மற்றும் அதற்குப் பிந்தைய பதிப்புகளில் ஊடாடும் வகையில் பயன்படுத்தப்படும் போது `apt-get` க்கு மாற்றாக பரிந்துரைக்கப்படுகிறது.

> மேலும் தகவல்: <https://manpages.debian.org/latest/apt/apt.8.html>.

- கிடைக்கக்கூடிய தொகுப்புகள் மற்றும் பதிப்புகளின் பட்டியலைப் புதுப்பிக்கவும் (மற்ற `apt` கட்டளைகளுக்கு முன் இதை இயக்க பரிந்துரைக்கப்படுகிறது):

```bash
sudo apt update
```

- கொடுக்கப்பட்ட தொகுப்பைத் தேடுங்கள்:

```bash
apt search நிரல்தொகுப்பு
```

- தொகுப்பிற்கான தகவலைக் காட்டு:

```bash
apt show நிரல்தொகுப்பு
```

- தொகுப்பை நிறுவவும் அல்லது கிடைக்கும் சமீபத்திய பதிப்பிற்கு புதுப்பிக்கவும்:

```bash
sudo apt install நிரல்தொகுப்பு
```

- ஒரு தொகுப்பை அகற்று ('purge' ஐப் பயன்படுத்தி அதன் உள்ளமைவு கோப்புகளையும் நீக்குகிறது):

```bash
sudo apt remove நிரல்தொகுப்பு
```

- நிறுவப்பட்ட அனைத்து தொகுப்புகளையும் அவற்றின் புதிய கிடைக்கக்கூடிய பதிப்புகளுக்கு மேம்படுத்தவும்:

```bash
sudo apt upgrade
```

- அனைத்து தொகுப்புகளையும் பட்டியலிடுங்கள்:

```bash
apt list
```

- நிறுவப்பட்ட தொகுப்புகளை பட்டியலிடுங்கள்:

```bash
apt list --installed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | apt: add Tamil translation (#8294) | 2022-08-05T09:08:49 | [812e191d27b7](https://github.com/tldr-pages/tldr/commit/812e191d27b78abedeebfe6f9b0e2b69c47b4884)

