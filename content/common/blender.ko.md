---
author: ['Schneider', 'lch7167', 'bl-ue', 'marchersimon']
date: 1625253777
title: "blender, TLDR Pages"
description: "blender, Blender 3D 컴퓨터 그래픽스 어플리케이션의 커맨드라인 인터페이스. 인자는 주어진 순서대로 실행."
categories: "common"
---
> 더 많은 정보: <https://docs.blender.org/manual/en/latest/advanced/command_line/>.

- UI를 로드하지 않고 background에서 애니메이션의 모든 프레임을 렌더링.(출력은 `/tmp`에 저장):

```bash
blender -b 파일명.blend -a
```

- .blend 파일에 대한 경로 (`//`)에서 특정 이미지 명명 패턴을 사용하여 애니메이션 렌더링:

```bash
blender -b 파일명.blend -o //render/frame_###.png -a
```

- 기존 디렉토리에 저장된 단일 이미지로 애니메이션의 10번째 프레임 렌더링(절대 경로):

```bash
blender -b 파일명.blend -o /출력_디렉토리/의/경로 -f 10
```

- 기존 디렉토리에 저장된 JPEG 이미지로 애니메이션의 두번째 마지막 프레임 렌더링(상대 경로):

```bash
blender -b 파일명.blend -o //출력_디렉토리 -F JPEG -f -2
```

- 프레임 10에서 시작하여 프레임 500에서 끝나는 특정 장면의 애니메이션 렌더링:

```bash
blender -b 파일명.blend -S 씬_이름 -s 10 -e 500 -a
```

- Python 표현식을 전달하여 특정 해상도로 애니메이션 렌더링:

```bash
blender -b 파일명.blend --python-expr 'import bpy; bpy.data.scenes[0].render.resolution_percentage = 25' -a
```

- Python 콘솔을 사용하여 터미널에서 대화형 Blender 세션 시작(시작 후`import bpy` 수행):

```bash
blender -b --python-console
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3564) | 2019-11-18T02:50:21 | [894df52f44af](https://github.com/tldr-pages/tldr/commit/894df52f44af2b32579b1009d539956058766205)

