---
author: ['Lucas Gabriel Schneider', 'b3nj4m1n', 'marchersimon']
date: 1619262596
title: "ffmpeg"
description: "ffmpeg, Programm zum konvertieren von Videos."
categories: "common"
---
> Weitere Informationen: <https://ffmpeg.org>.

- Extrahiere den Ton eines Videos und speichere ihn als MP3:

```bash
ffmpeg -i pfad/zu/video.mp4 -vn pfad/zu/audio.mp3
```

- Konvertiere Frames eines Videos oder Gifs zu individuellen, numerierten Bildern:

```bash
ffmpeg -i video.mpg|video.gif pfad/zu/frame_%d.png
```

- Kombiniere numerierte Bilder (`frame_1.jpg`, `frame_2.jpg`, etc) in ein Video oder Gif:

```bash
ffmpeg -i pfad/zu/frame_%d.jpg -f bild2 video.mpg|video.gif
```

- Extrahiere einen einzelnen Frame von einem Video bei mm:ss and speichere als 128x128 Bild:

```bash
ffmpeg -ss mm:ss -i pfad/zu/video.mp4 -frames 1 -s 128x128 -f bild2 pfad/zu/bild.png
```

- Trimme ein Video von mm:ss bis mm2:ss2 (Ohne -to bis zum Ende des Videos):

```bash
ffmpeg -ss mm1:ss1 -to mm2:ss2 -i video.mp4 -codec copy pfad/zu/output.mp4
```

- Konvertiere ein AVI Video zu MP4. AAC Audio @ 128kbit, h264 Video @ CRF 23:

```bash
ffmpeg -i pfad/zu/input_video.avi -codec:audio aac -b:audio 128k -codec:video libx264 -crf 23 pfad/zu/output_video.mp4
```

- Remuxe ein MKV Video zu MP4 ohne Audio oder Video streams neu zu codieren:

```bash
ffmpeg -i pfad/zu/input_video.mkv -codec copy pfad/zu/output_video.mp4
```

- Konvertiere ein MP4 video zu VP9. Für beste Qualität, nutze einen CRF Wert von 15 bis 35 und -b:video MUSS 0 sein:

```bash
ffmpeg -i pfad/zu/input_video.mp4 -codec:video libvpx-vp9 -crf 30 -b:video 0 -codec:audio libopus -vbr on -threads thread_anzahl pfad/zu/output_video.webm
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[b3nj4m1n](mailto:b3nj4m1n@gmx.net) | ffmpeg: add German translation | 2020-07-02T17:41:08 | [f87d8659d9df](https://github.com/tldr-pages/tldr/commit/f87d8659d9df3d455a5111bb306e366703521cc2)

