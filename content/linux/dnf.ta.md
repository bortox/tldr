---
author: ['K.B.Dharun Krishna']
date: 1659905070
title: "dnf"
description: "dnf, RHEL, Fedora மற்றும் CentOS க்கான தொகுப்பு மேலாண்மை பயன்பாடு (yum ஐ மாற்றுகிறது)."
categories: "linux"
---
> மேலும் விவரத்திற்கு: <https://dnf.readthedocs.io>.

- நிறுவப்பட்ட தொகுப்புகளை புதிய கிடைக்கக்கூடிய பதிப்புகளுக்கு மேம்படுத்தவும்:

```bash
sudo dnf upgrade
```

- முக்கிய வார்த்தைகள் மூலம் தொகுப்புகளைத் தேடுங்கள்:

```bash
dnf search முக்கிய வார்த்தைகள்
```

- தொகுப்பு பற்றிய விவரங்களைக் காண்பி:

```bash
dnf info நிரல்தொகுப்பு
```

- புதிய தொகுப்பை நிறுவவும் (அனைத்து அறிவுறுத்தல்களையும் தானாக உறுதிப்படுத்த `-y` ஐப் பயன்படுத்தவும்):

```bash
sudo dnf install நிரல்தொகுப்பு
```

- ஒரு தொகுப்பை அகற்று:

```bash
sudo dnf remove நிரல்தொகுப்பு
```

- நிறுவப்பட்ட தொகுப்புகளை பட்டியலிடுங்கள்:

```bash
dnf list --installed
```

- கொடுக்கப்பட்ட கோப்பை எந்த தொகுப்புகள் வழங்குகின்றன என்பதைக் கண்டறியவும்:

```bash
dnf provides கோப்பு
```

- அனைத்து கடந்த செயல்பாடுகளையும் காண்க:

```bash
dnf history
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | pages.ta/*: fix more information Tamil translation (#8320) | 2022-08-07T22:44:30 | [e2a742ca82e2](https://github.com/tldr-pages/tldr/commit/e2a742ca82e2889a2d605962a45196e64b7579e4)
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | dnf: add Tamil translation (#8293) | 2022-08-05T08:52:39 | [8af11805636b](https://github.com/tldr-pages/tldr/commit/8af11805636b2dd120fa3c831098a77f13181d4c)

