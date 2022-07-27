---
author: ['Michał Gąsior']
date: 1637057745
title: "ykman, TLDR Pages"
description: "ykman, The YubiKey Manager can be used to configure all aspects of the YubiKey."
categories: "common"
---
> More information: <https://docs.yubico.com/software/yubikey/tools/ykman/index.html>.

- Get information from YubiKey:

```bash
ykman info
```

- Get information for a given application from YubiKey:

```bash
ykman fido|oath|openpgp|otp|piv info
```

- Get a list of enabled applications over NFC from YubiKey:

```bash
ykman config nfc --list
```

- Enable application over USB on YubiKey:

```bash
ykman config usb --enable OTP|U2F|FIDO2|OATH|PIV|OPENPGP|HSMAUTH
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Michał Gąsior](mailto:rogacz@gmail.com) | ykinfo, ykman: add page (#6870) | 2021-11-16T11:15:45 | [7f0b233ea1e3](https://github.com/tldr-pages/tldr/commit/7f0b233ea1e3fe44b7c7e3186046b4da4f423b6a)

