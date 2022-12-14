---
author: ['Siddharth Johri']
date: 1635017237
title: "ssh"
description: "ssh, सिक्योर शेल एक प्रोटोकॉल है जिसका उपयोग रिमोट सिस्टम पर सुरक्षित रूप से लॉग ऑन करने के लिए किया जाता है।"
categories: "common"
---
> इसका उपयोग रिमोट सर्वर पर लॉगिंग या कमांड निष्पादित करने के लिए किया जा सकता है।

> अधिक जानकारी: <https://man.openbsd.org/ssh>।

- रिमोट सर्वर से कनेक्ट करें:

```bash
ssh उपयोगकर्ता_नाम@रिमोट_होस्ट
```

- एक विशिष्ट पहचान (निजी कुंजी) के साथ एक दूरस्थ सर्वर से कनेक्ट करें:

```bash
ssh -i फ़ाइल/का/स्थान उपयोगकर्ता_नाम@रिमोट_होस्ट
```

- किसी विशिष्ट पोर्ट का उपयोग करके किसी दूरस्थ सर्वर से कनेक्ट करें:

```bash
ssh उपयोगकर्ता_नाम@रिमोट_होस्ट -p 2222
```

- रिमोट सर्वर पर [t] ty आवंटन के साथ एक कमांड चलाएँ जो रिमोट कमांड के साथ इंटरेक्शन की अनुमति देता है:

```bash
ssh उपयोगकर्ता_नाम@रिमोट_होस्ट -t कमांड कमांड_विकल्प
```

- SSH टनलिंग: डायनेमिक पोर्ट फ़ॉरवर्डिंग (`लोकलहोस्ट: 1080 पर SOCKS प्रॉक्सी):

```bash
ssh -D 1080 उपयोगकर्ता_नाम@रिमोट_होस्ट
```

- एसएसएच टनलिंग: एक विशिष्ट पोर्ट (`लोकलहोस्ट: 9999` से `example.org:80`) को अग्रेषित करें, साथ ही छद्म-[टी] ty आवंटन और रिमोट कमांड के निष्पादन [एन] को अक्षम करने के साथ:

```bash
ssh -L 9999:example.org:80 -N -T उपयोगकर्ता_नाम@रिमोट_होस्ट
```

- SSH जंपिंग: एक जम्पहोस्ट के माध्यम से एक दूरस्थ सर्वर से कनेक्ट करें (कई जंप हॉप्स को अल्पविराम वर्णों से अलग करके निर्दिष्ट किया जा सकता है):

```bash
ssh -J उपयोगकर्ता_नाम@जंप_होस्ट उपयोगकर्ता_नाम@रिमोट_होस्ट
```

- एजेंट अग्रेषण: रिमोट मशीन को प्रमाणीकरण जानकारी अग्रेषित करें (उपलब्ध विकल्पों के लिए `man ssh_config` देखें):

```bash
ssh -A उपयोगकर्ता_नाम@रिमोट_होस्ट
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Siddharth Johri](mailto:34266009+JodisKripe@users.noreply.github.com) | scp, ssh: add Hindi translation (#7062) | 2021-10-23T21:27:17 | [e42670fd5235](https://github.com/tldr-pages/tldr/commit/e42670fd5235e6ab30f140b18b037e14ad486065)

