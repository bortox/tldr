---
author: ['K.B.Dharun Krishna']
date: 1660527965
title: "todoist"
description: "todoist, கட்டளை வரியிலிருந்து Todoist ஐ அணுகவும்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://github.com/sachaos/todoist>.

- பணியைச் சேர்க்கவும்:

```bash
todoist add "பணி_பெயர்"
```

- லேபிள், திட்டம் மற்றும் நிலுவைத் தேதியுடன் அதிக முன்னுரிமை பணியைச் சேர்க்கவும்:

```bash
todoist add "பணி_பெயர்" --priority 1 --label-ids "லேபிள்_ஐடி" --project-name "திட்டத்தின்_பெயர்" --date "நாளை காலை 9 மணி"
```

- Aவிரைவு பயன்முறையில் லேபிள், திட்டப்பணி மற்றும் நிலுவைத் தேதியுடன் அதிக முன்னுரிமைப் பணியைச் சேர்க்கவும்:

```bash
todoist quick '#திட்டத்தின்_பெயர் "நாளை காலை 9 மணி" p1 பணி_பெயர் @லேபிள்_பெயர்'
```

- தலைப்பு மற்றும் வண்ணத்துடன் அனைத்து பணிகளையும் பட்டியலிடுங்கள்:

```bash
todoist --header --color list
```

- அனைத்து உயர் முன்னுரிமைப் பணிகளையும் பட்டியலிடுங்கள்:

```bash
todoist list --filter p1
```

- குறிப்பிடப்பட்ட லேபிளைக் கொண்ட இன்றைய பணிகளை அதிக முன்னுரிமையுடன் பட்டியலிடுங்கள்:

```bash
todoist list --filter '(@லேபிள்_பெயர் | இன்று) & p1'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | todo,todoist,todoman: add Tamil translation (#8348) | 2022-08-15T03:46:05 | [18bc69730b9b](https://github.com/tldr-pages/tldr/commit/18bc69730b9bfe76264a7b3fe8d9ee3d7468f829)

