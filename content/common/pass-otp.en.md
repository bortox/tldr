---
author: ['Quentin']
date: 1603542297
title: "pass otp, TLDR Pages"
description: "pass otp, A pass extension for managing one-time-password (OTP) tokens."
categories: "common"
---
> More information: <https://github.com/tadfisher/pass-otp#readme>.

- Prompt for an otpauth URI token and create a new pass file:

```bash
pass otp insert path/to/pass
```

- Prompt for an otpauth URI token and append to an existing pass file:

```bash
pass otp append path/to/pass
```

- Print a 2FA code using the OTP token in a pass file:

```bash
pass otp path/to/pass
```

- Copy and don't print a 2FA code using the OTP token in a pass file:

```bash
pass otp --clip path/to/pass
```

- Display a QR code using the OTP token stored in a pass file:

```bash
pass otp uri --qrcode path/to/pass
```

- Prompt for an OTP secret value specifying issuer and account (at least one must be specified) and append to existing pass file:

```bash
pass otp append --secret --issuer issuer_name --account account_name path/to/pass
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Quentin](mailto:quentin.bettoum@mailo.com) | pass-otp: fix typo (#4770) | 2020-10-24T14:24:57 | [5e96baeca13a](https://github.com/tldr-pages/tldr/commit/5e96baeca13a1d765e50ceedac4a61fc2088d220)
[Quentin](mailto:63603941+quentin-bettoum@users.noreply.github.com) | pass-otp: add page (#4232) | 2020-08-01T10:19:19 | [0886200ed911](https://github.com/tldr-pages/tldr/commit/0886200ed911533f62b74da60392874959b12477)

