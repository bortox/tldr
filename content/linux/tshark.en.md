---
author: ['fejx', 'Tigran Tch', 'CleanMachine1', 'Anatoli Babenia', 'bl-ue']
date: 1624920504
title: "tshark, TLDR Pages"
description: "tshark, Packet analysis tool, CLI version of Wireshark."
categories: "linux"
---
> More information: <https://tshark.dev/>.

- Monitor everything on localhost:

```bash
tshark
```

- Only capture packets matching a specific capture filter:

```bash
tshark -f 'udp port 53'
```

- Only show packets matching a specific output filter:

```bash
tshark -Y 'http.request.method == "GET"'
```

- Decode a TCP port using a specific protocol (e.g. HTTP):

```bash
tshark -d tcp.port==8888,http
```

- Specify the format of captured output:

```bash
tshark -T json|text|ps|…
```

- Select specific fields to output:

```bash
tshark -T fields|ek|json|pdml -e http.request.method -e ip.src
```

- Write captured packet to a file:

```bash
tshark -w path/to/file
```

- Analyze packets from a file:

```bash
tshark -r filename.pcap
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/t*: add information link (#6166) | 2021-06-29T00:48:24 | [d86d3d6206bd](https://github.com/tldr-pages/tldr/commit/d86d3d6206bdf76257ce480be4a8a71d2d4fdda6)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[fejx](mailto:florian.jhn@gmail.com) | Change all occurrences of file_name to filename (#4059) | 2020-05-22T14:31:24 | [4e1662b729ba](https://github.com/tldr-pages/tldr/commit/4e1662b729ba2bc23f7c12f606d41a86a613f8ea)
[Anatoli Babenia](mailto:anatoli@rainforce.org) | tshark: add capture filter (#2872) | 2019-09-18T17:09:38 | [f840d3d0dc10](https://github.com/tldr-pages/tldr/commit/f840d3d0dc10962a05ff76c6a3424485d13c254b)
[Tigran Tch](mailto:nargitinthenight@gmail.com) | tshark: add page (#2758) | 2019-02-07T15:27:17 | [0428b0379af8](https://github.com/tldr-pages/tldr/commit/0428b0379af8a49468a970aa0728a3cf093f486d)

