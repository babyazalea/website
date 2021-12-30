---
title: macOS에 설치하기
description: macOS에 플러터(Flutter)를 설치하는 방법
short-title: macOS
next:
  title: Set up an editor
  path: /get-started/editor
---

{% assign os = 'macos' -%}

## 시스템 최소 요구 사항

플러터(Flutter)를 설치하고 실행하기 위해서는
아래의 최소 요구 조건에 충족하는 개발 환경이 필요합니다:

- **운영체제**: macOS
- **여유 저장 공간**: 2.8 GB (IDE나 기타 개발 도구가 차지하는 저장 공간은 별도로 필요합니다.)
- **Tools**: 플러터(Flutter)는 설치와 업그레이드를 위해 `git`을 사용합니다. `git`이 포함된 [Xcode][]을 설치해도 되지만, 따로 [`git` 설치][]를 해도 괜찮습니다.

{{site.alert.important}}
  [Apple M1 processor][]가 탑재된 신형 Mac에 설치를 진행하고 있는 중이라면,
  [Apple Silicon 사용자를 위한 도움말][]에서
  새로운 Apple Silicon 아키텍쳐에 관한
  유용한 정보를 얻을 수 있습니다.
{{site.alert.end}}

{% include_relative _get-sdk-mac.md %}

{% include_relative _path-mac.md %}

## Platform setup

macOS에서는 iOS, Android, web(개발자 프리뷰)용 플러터(Flutter) 앱을 모두 개발할 수 있습니다.
플러터(Flutter) 앱을 만들고 실행하기 위해
아래의 플랫폼 중에서 최소 하나의 플랫폼을 골라 설치를 완료합니다.

{% include_relative _ios-setup.md %}

{% include_relative _android-setup.md %}

{% include_relative _macos-desktop-setup.md %}

{% include_relative _web-setup.md %}

## Next step

편집기 설정에 대해 알아봅니다.

[Apple M1 processor]: https://www.apple.com/mac/m1
[Apple Silicon 사용자를 위한 도움말]: {{site.repo.flutter}}/wiki/Developing-with-Flutter-on-Apple-Silicon
[Xcode]: {{site.apple-dev}}/xcode/
[`git` 설치]: https://git-scm.com/download/mac