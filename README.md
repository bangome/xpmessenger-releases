# Xp Messenger — 배포본

Xp 메신저의 **설치본과 자동 업데이트 파일만** 두는 저장소입니다.
애플리케이션 소스 코드는 비공개 저장소에서 관리합니다.

## 설치

[Releases](https://github.com/bangome/xpmessenger-releases/releases/latest) 에서 받으세요.

| 파일 | 설명 |
| --- | --- |
| `XpMessenger-Web-Setup-<버전>.exe` | 웹 설치본(약 1MB). 실행하면 본체를 내려받아 설치하며 **자동 업데이트를 지원**합니다. |
| `XpMessenger-portable.exe` | 포터블. 설치 없이 실행하지만 자동 업데이트는 되지 않습니다. |

## 자동 업데이트

설치본은 이 저장소의 최신 릴리즈를 확인해 스스로 업데이트합니다.
저장소가 공개라 앱에 인증 토큰을 넣을 필요가 없습니다.

## 릴리즈 방법

소스 저장소에서 `npm run release` 를 실행하면 빌드 산출물이 이 저장소로 업로드됩니다.
