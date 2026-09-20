# Pi Reader

![Pi Reader](assets/icon.png)

만화와 이미지를 편안하게 읽는 로컬 뷰어입니다. 이 저장소는 **설치 파일 배포 전용**이며 앱 소스는 포함하지 않습니다.

[최신 버전 다운로드](https://github.com/cherub8128/Pi-Reader-Releases/releases/latest)

- 폴더별 서재와 첫 이미지 표지, 읽던 위치 저장
- 한 장·두 장·웹툰 보기, 좌우 읽기 방향, 확대·회전, 책갈피와 메모
- ZIP/CBZ/RAR/CBR과 JPG·PNG·WebP·GIF·BMP·AVIF
- mm 단위 여백·크기·배치, 여러 이미지 한 장 인쇄, 흑백 미리보기와 PDF 저장
- Noto Sans / Noto Sans KR 내장, 인터넷 연결 없이 사용

## 다운로드 선택

| 운영체제 | 파일 | 검증 범위 |
| --- | --- | --- |
| Windows x64 | `windows-x64-setup.exe` / `windows-x64-portable.exe` | 실제 앱 실행·독서·재시작·PDF 출력 검증 |
| Linux x64 | `linux-x64.deb` / `linux-x64.tar.gz` | 패키지 구조·실행 권한·내용 검증, Linux 실행 미검증 |
| macOS Apple Silicon | `mac-arm64-adhoc.zip` | 시험 배포, macOS 실행 미검증 |
| macOS Intel | `mac-x64-adhoc.zip` | 시험 배포, macOS 실행 미검증 |

모든 파일은 로컬에서 만들었습니다. GitHub Actions는 사용하지 않습니다. Windows 설치 파일은 인증서 서명이 없으며 macOS 앱은 ad-hoc 서명만 있고 Apple 공증은 없습니다. 운영체제의 개발자 확인 경고가 나타날 수 있습니다.

Windows에서 파일 연결을 사용하려면 설치형 버전을 설치한 뒤 기본 앱으로 선택합니다. 탐색기 썸네일과 앱 배지는 Windows 설정 및 이미지 코덱에 따라 표시됩니다. 원본 파일을 수정하지 않습니다.

실제 종이 인쇄는 프린터·드라이버에 따라 다르며 물리 프린터 테스트는 하지 않았습니다. 암호화·분할 압축, PDF 입력, 7z는 지원하지 않습니다. ZIP은 최대 2 GiB, RAR은 256 MiB, 개별 이미지는 64 MiB까지입니다.

다운로드 파일 무결성은 릴리스의 `SHA256SUMS.txt`로 확인할 수 있습니다. 타사 라이선스와 Noto OFL 고지는 앱에 포함되어 있습니다.

Linux에서는 deb 설치 패키지를 권장합니다. tar.gz를 사용할 경우 포함된 README의 sandbox 소유권·권한 설정을 먼저 적용해야 합니다. sandbox를 끄는 실행 옵션은 제공하지 않습니다.

