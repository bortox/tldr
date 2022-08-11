---
author: ['K.B.Dharun Krishna']
date: 1660133902
title: "rpm-ostree"
description: "rpm-ostree, ஒரு கலப்பின படம்/தொகுப்பு அமைப்பு."
categories: "linux"
---
> ostree வரிசைப்படுத்தல்கள், தொகுப்பு அடுக்குகள், கோப்பு முறைமை மேலடுக்குகள் மற்றும் துவக்க உள்ளமைவு ஆகியவற்றை நிர்வகிக்கவும்.

> மேலும் விவரத்திற்கு: <https://coreos.github.io/rpm-ostree/administrator-handbook/>.

- துவக்க ஏற்றியில் தோன்றும் வரிசையில் `rpm-ostree` வரிசைப்படுத்தல்களைக் காட்டு:

```bash
rpm-ostree status
```

- காலாவதியான மற்றும் புதுப்பிக்கக்கூடிய தொகுப்புகளைக் காட்டு:

```bash
rpm-ostree upgrade --preview
```

- மேம்படுத்தப்பட்ட தொகுப்புகளுடன் ஒரு புதிய `ostree` வரிசைப்படுத்தலைத் தயாரித்து அதில் மீண்டும் துவக்கவும்:

```bash
rpm-ostree upgrade --reboot
```

- முந்தைய ostree வரிசைப்படுத்தலில் மீண்டும் துவக்கவும்:

```bash
rpm-ostree rollback --reboot
```

- ஒரு புதிய ostree வரிசைப்படுத்தலில் ஒரு தொகுப்பை நிறுவி அதில் மீண்டும் துவக்கவும்:

```bash
rpm-ostree install தொகுப்பு --reboot
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | rpm-ostree: add Tamil translation (#8329) | 2022-08-10T14:18:22 | [b1deb085deaa](https://github.com/tldr-pages/tldr/commit/b1deb085deaab69b1705124c901144d31878b09b)

