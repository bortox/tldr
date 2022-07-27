---
author: ['mxmxyz', 'Lucas Gabriel Schneider', 'bl-ue']
date: 1612369364
title: "ffmpeg, TLDR Pages"
description: "ffmpeg, Tool per convertire audio e video."
categories: "common"
---
> Maggiori informazioni: <https://ffmpeg.org>.

- Estrai l'audio da un video e salvalo come MP3:

```bash
ffmpeg -i video.mp4 -vn audio.mp3
```

- Converti i fotogrammi di un video o una GIF in una serie di immagini numerate:

```bash
ffmpeg -i video.mpg|video.gif foto_%d.png
```

- Sequenzia immagini numerate (`foto_1.jpg`, `foto_2.jpg`, ecc) per creare un video o una GIF:

```bash
ffmpeg -i frame_%d.jpg -f image2 video.mpg|video.gif
```

- Estrai un singolo fotogramma da un video al timestamp mm:ss e salvalo come immagine di dimensioni 128x128:

```bash
ffmpeg -ss mm:ss -i video.mp4 -frames 1 -s 128x128 -f image2 image.png
```

- Taglia un video da un momento iniziale mm:ss a un momento finale mm:ss (rimuovi la flag -to per tagliare fino alla fine):

```bash
ffmpeg -ss mm:ss -to mm2:ss2 -i video.mp4 -codec copy output.mp4
```

- Converti un video AVI a MP4. Audio AAC a 128kbit, video h264 a CRF 23:

```bash
ffmpeg -i input_video.avi -codec:audio aac -b:audio 128k -codec:video libx264 -crf 23 output_video.mp4
```

- Effettua un remux di un video MKV a MP4 senza re-encodare gli stream audio o video:

```bash
ffmpeg -i input_video.mkv -codec copy output_video.mp4
```

- Converti un video MP4 a codec VP9. Per ottenere la migliore qualità possibile, usa un valore di CRF (consigliabile tra 15-35) e -b:video DEVE essere 0:

```bash
ffmpeg -i input_video.mp4 -codec:video libvpx-vp9 -crf 30 -b:video 0 -codec:audio libopus -vbr on -threads number_of_threads output_video.webm
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[mxmxyz](mailto:mxmxyzgxyzt@gmail.com) | 6 translations to italian | 2020-09-09T02:42:53 | [ae3ba00236f1](https://github.com/tldr-pages/tldr/commit/ae3ba00236f1e305ae16d0a317d345bffe88c857)

