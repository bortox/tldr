---
author: ['K.B.Dharun Krishna']
date: 1659919212
title: "ufw"
description: "ufw, சிக்கலற்ற ஃபயர்வால்."
categories: "linux"
---
> ஃபயர்வாலின் உள்ளமைவை எளிதாக்குவதை நோக்கமாகக் கொண்ட ஐப்டேபிள்களுக்கான முன்பக்கம்.

> மேலும் விவரத்திற்கு:  <https://wiki.ubuntu.com/UncomplicatedFirewall>.

- `ufw` ஐ இயக்கு:

```bash
ufw enable
```

- `ufw` ஐ முடக்கு:

```bash
ufw disable
```

- `ufw` விதிகளை அவற்றின் எண்களுடன் காட்டு:

```bash
ufw status numbered
```

- சேவையை அடையாளம் காட்டும் கருத்துடன் இந்த ஹோஸ்டில் உள்ள போர்ட் 5432 இல் உள்வரும் போக்குவரத்தை அனுமதிக்கவும்:

```bash
ufw allow 5432 comment "சேவை"
```

- போர்ட் 22 இல், இந்த ஹோஸ்டில் உள்ள எந்த முகவரிக்கும் 192.168.0.4 இலிருந்து டிசிபி போக்குவரத்தை மட்டும் அனுமதிக்கவும்:

```bash
ufw allow proto டிசிபி from 192.168.0.4 to ஏதேனும் port 22
```

- இந்த ஹோஸ்டில் போர்ட் 80 இல் போக்குவரத்தை நிராகரிக்கவும்:

```bash
ufw deny 80
```

- 8412:8500 வரம்பில் உள்ள துறைமுகங்களுக்கு அனைத்து யுடிபி போக்குவரத்தையும் நிராகரிக்கவும்:

```bash
ufw deny proto யுடிபி from ஏதேனும் to ஏதாவது port 8412:8500
```

- ஒரு குறிப்பிட்ட விதியை நீக்கவும். விதி எண்ணை `ufw status numbered` கட்டளையிலிருந்து மீட்டெடுக்கலாம்:

```bash
ufw delete விதி_எண்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | ufw: add Tamil translation (#8319) | 2022-08-08T02:40:12 | [06665c0a5909](https://github.com/tldr-pages/tldr/commit/06665c0a5909b49cea12aca854b163897fb2a866)

