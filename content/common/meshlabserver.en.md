---
author: ['Juri', 'bl-ue', 'Waldir Pimenta']
date: 1634444636
title: "meshlabserver, TLDR Pages"
description: "meshlabserver, Command-line interface for the MeshLab 3D mesh processing software."
categories: "common"
---
> More information: <https://manned.org/meshlabserver>.

- Convert an STL file to an OBJ file:

```bash
meshlabserver -i input.stl -o output.obj
```

- Convert a WRL file to a OFF file, including the vertex and face normals in the output mesh:

```bash
meshlabserver -i input.wrl -o output.off -om vn fn
```

- Dump a list of all the available processing filters into a file:

```bash
meshlabserver -d filename
```

- Process a 3D file using a filter script created in the MeshLab GUI (Filters > Show current filter script > Save Script):

```bash
meshlabserver -i input.ply -o output.ply -s filter_script.mlx
```

- Process a 3D file using a filter script, writing the output of the filters into a log file:

```bash
meshlabserver -i input.x3d -o output.x3d -s filter_script.mlx -l logfile
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | meshlabserver, nkf, obs, pax, pdfimages, pinky, pssh, s, sd, sendmail, sftp: add link (#6971) | 2021-10-17T06:23:56 | [977d4212d52c](https://github.com/tldr-pages/tldr/commit/977d4212d52c031de053f549d819b8b0e18ce184)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | meshlabserver: add page (#1035) * meshlabserver: create page * fixup: typo in command name * fixes per PR review | 2016-12-22T00:19:53 | [5552c19ff12a](https://github.com/tldr-pages/tldr/commit/5552c19ff12a08a77443e01cff2361b22ce8501f)

