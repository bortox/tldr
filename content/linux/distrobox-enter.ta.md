---
author: ['K.B.Dharun Krishna']
date: 1661431351
title: "distrobox-enter"
description: "distrobox-enter, டிஸ்ட்ரோபாக்ஸ் கொள்கலனில் கட்டளையை இயக்கவும்."
categories: "linux"
---
> முன்னிருப்பு கட்டளை செயல்படுத்தப்பட்டது உங்கள் ஷெல் ஆகும், இயக்குவதற்கு வெவ்வேறு ஷெல்கள் அல்லது முழு கட்டளைகளையும் குறிப்பிடவும். ஸ்கிரிப்ட், பயன்பாடு அல்லது சேவையில் பயன்படுத்தினால், tty மற்றும் ஊடாடும் தன்மையை முடக்க --headless பயன்முறையைக் குறிப்பிடலாம்.

> மேலும் விவரத்திற்கு: <https://distrobox.privatedns.org>.

- ஒரு டிஸ்ட்ரோபாக்ஸை உள்ளிட்டு, `sh -l` ஐ இயக்கவும்:

```bash
distrobox-enter container-name -- sh -l
```

- ஒரு tty ஐ உடனடியாகச் செய்யாமல் ஒரு டிஸ்ட்ரோபாக்ஸை உள்ளிடவும்:

```bash
distrobox-enter -H container-name -- uptime -p
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | distrobox-*: add Tamil translation (#8377) | 2022-08-25T14:42:31 | [ce1f5f01f58b](https://github.com/tldr-pages/tldr/commit/ce1f5f01f58bf4f39c81855206e6525627a24cf6)

