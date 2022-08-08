---
author: ['K.B.Dharun Krishna']
date: 1659905070
title: "flatpak"
description: "flatpak, பிளாட்பேக் பயன்பாடுகள் மற்றும் இயக்க நேரங்களை உருவாக்கவும், நிறுவவும் மற்றும் இயக்கவும்."
categories: "linux"
---
> மேலும் விவரத்திற்கு: <https://docs.flatpak.org/en/latest/flatpak-command-reference.html#flatpak>.

- நிறுவப்பட்ட பயன்பாட்டை இயக்கவும்:

```bash
flatpak run பெயர்
```

- தொலைநிலை மூலத்திலிருந்து பயன்பாட்டை நிறுவவும்:

```bash
flatpak install ரிமோட் பெயர்
```

- நிறுவப்பட்ட அனைத்து பயன்பாடுகளையும் இயக்க நேரங்களையும் பட்டியலிடுங்கள்:

```bash
flatpak list
```

- நிறுவப்பட்ட அனைத்து பயன்பாடுகளையும் இயக்க நேரங்களையும் புதுப்பிக்கவும்:

```bash
flatpak update
```

- தொலைநிலை மூலத்தைச் சேர்க்கவும்:

```bash
flatpak remote-add --if-not-exists ரிமோட்_பெயர் ரிமோட்_url
```

- உள்ளமைக்கப்பட்ட அனைத்து தொலை மூலங்களையும் பட்டியலிடுங்கள்:

```bash
flatpak remote-list
```

- நிறுவப்பட்ட பயன்பாட்டை அகற்றவும்:

```bash
flatpak remove பெயர்
```

- நிறுவப்பட்ட பயன்பாட்டைப் பற்றிய தகவலைக் காட்டு:

```bash
flatpak info பெயர்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | pages.ta/*: fix more information Tamil translation (#8320) | 2022-08-07T22:44:30 | [e2a742ca82e2](https://github.com/tldr-pages/tldr/commit/e2a742ca82e2889a2d605962a45196e64b7579e4)
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | flatpak: add Tamil translation (#8318) | 2022-08-07T17:46:08 | [dfe23221440b](https://github.com/tldr-pages/tldr/commit/dfe23221440be3fa05a9e54ba4fd392c6555ba6c)

