---
author: ['K.B.Dharun Krishna']
date: 1660908895
title: "fdisk"
description: "fdisk, பகிர்வு அட்டவணைகள் மற்றும் பகிர்வுகளை ஹார்ட் டிஸ்கில் நிர்வகிப்பதற்கான ஒரு நிரல்."
categories: "linux"
---
> மேலும் பார்க்கவும்: `partprobe`.

> மேலும் விவரத்திற்கு: <https://manned.org/fdisk>.

- பகிர்வுகளின் பட்டியல்:

```bash
sudo fdisk -l
```

- பகிர்வு கையாளுதலைத் தொடங்கவும்:

```bash
sudo fdisk /dev/sdX
```

- ஒரு வட்டை பகிர்ந்தவுடன், ஒரு பகிர்வை உருவாக்கவும்:

```bash
n
```

- ஒரு வட்டை பகிர்ந்தவுடன், நீக்க ஒரு பகிர்வை தேர்ந்தெடுக்கவும்:

```bash
d
```

- ஒரு வட்டை பகிர்ந்தவுடன், பகிர்வு அட்டவணையைப் பார்க்கவும்:

```bash
p
```

- ஒரு வட்டை பகிர்ந்தவுடன், செய்யப்பட்ட மாற்றங்களை எழுதவும்:

```bash
w
```

- ஒரு வட்டை பகிர்ந்தவுடன், செய்யப்பட்ட மாற்றங்களை நிராகரிக்கவும்:

```bash
q
```

- ஒரு வட்டை பகிர்ந்தவுடன், உதவி மெனுவைத் திறக்கவும்:

```bash
m
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | fdisk, fwupdmgr: add Tamil translation (#8371) | 2022-08-19T13:34:55 | [dfe8cd573cab](https://github.com/tldr-pages/tldr/commit/dfe8cd573cab2210356ff063219c19801ece899b)

