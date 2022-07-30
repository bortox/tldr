---
author: ['Krzysztof Bociurko']
date: 1604237455
title: "youtube-dl"
description: "youtube-dl, Pobieraj wideo i audio z YouTube i podobnych portali"
categories: "common"
---
> Więcej informacji: <http://rg3.github.io/youtube-dl/>.

- Pobierz plik wideo lub wszystkie pliki z playlisty:

```bash
youtube-dl 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Listuj wszystkie formaty dostępne dla filmu lub playlisty:

```bash
youtube-dl --list-formats 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Pobierz wideo lub playlistę w wybranej jakości:

```bash
youtube-dl --format "best[height<=480]" 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Pobierz audio z wideo w formacie mp3:

```bash
youtube-dl -x --audio-format mp3 'url'
```

- Pobierz wideo ze ścieżką audio złączone w jendym pliku w najlepszej dostępnej jakości:

```bash
youtube-dl -f bestvideo+bestaudio 'url'
```

- Pobierz wideo jako pliki MP4 i nazwij wedle schematu:

```bash
youtube-dl --format mp4 -o "%(title)s by %(uploader)s on %(upload_date)s in %(playlist)s.%(ext)s" 'url'
```

- Pobierz plik razem z napisami:

```bash
youtube-dl --sub-lang en --write-sub 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Pobierz ścieżkę dźwiękową ze wszystkich filmów z playlisty:

```bash
youtube-dl -i --extract-audio --audio-format mp3 -o "%(title)s.%(ext)s" 'adres_url_playlisty'
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | youtube-dl: add Polish translation (#4900) | 2020-11-01T14:30:55 | [4b06377bad69](https://github.com/tldr-pages/tldr/commit/4b06377bad69922dc63d93cf8e9979cb218652ca)

