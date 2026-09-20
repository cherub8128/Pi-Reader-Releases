# Third-party notices / 제3자 구성요소 고지

Pi Reader 자체에는 LICENSE.txt의 무료 사용 독점 라이선스가 적용됩니다. 아래 구성요소는 그 약관으로 재라이선스하지 않으며, 각 원래 라이선스와 법률상 권리가 우선합니다. 앱의 약관·라이선스 화면에서도 이 고지와 원문을 오프라인으로 읽을 수 있습니다.

## Shipped application libraries

| Component | Version | License | Complete notice |
| --- | --- | --- | --- |
| React | 19.3.0 | MIT | licenses/React-MIT.txt |
| React DOM | 19.3.0 | MIT | licenses/React-DOM-MIT.txt |
| Scheduler | 0.28.0 | MIT | licenses/Scheduler-MIT.txt |
| Lucide React icons | 1.47.0 | ISC (additional notices retained) | licenses/Lucide-ISC.txt |
| yauzl | 3.4.0 | MIT | licenses/yauzl-MIT.txt |
| pend | 1.2.0 | MIT | licenses/pend-MIT.txt |
| node-unrar-js wrapper | 2.0.2 | MIT | licenses/node-unrar-js-MIT.txt |
| UnRAR extractor | 6.1.7 | UnRAR freeware (RAR creation restricted) | licenses/UnRAR.txt |
| Emscripten generated runtime | bundled by node-unrar-js | MIT / NCSA | licenses/Emscripten.txt |
| Noto Sans Variable | Fontsource 5.3.0 | SIL OFL 1.1 | licenses/Noto-Sans-OFL.txt |
| Noto Sans KR Variable | Fontsource 5.3.0 | SIL OFL 1.1 | licenses/Noto-Sans-KR-OFL.txt |

Noto fonts are bundled unmodified and loaded locally. No font CDN is used. The fonts retain OFL 1.1; the proprietary Pi Reader license does not restrict their separate use, modification or redistribution under OFL. Font source: https://github.com/notofonts. Fontsource package source: https://github.com/fontsource/font-files.

## Desktop runtime

Electron 44.4.3 is distributed under MIT with Chromium, Node.js and additional components under their respective licenses. We redistribute the official Electron runtimes with application packaging/branding and ad-hoc signatures; we do not change their runtime code. LICENSE.electron.txt and LICENSES.chromium.html shipped with the official runtime are retained beside the Windows/Linux executable or in the macOS app resources. Those complete runtime notices remain authoritative.

Runtime source and build references: https://github.com/electron/electron/tree/v44.4.3. Its DEPS file identifies the matching Chromium/Node/V8 source revisions and the patches directory identifies Electron patches. Developer tools such as Vite, TypeScript, electron-builder, Playwright, sharp, png-to-ico and rcodesign are build/test tools, not app UI/runtime dependencies. The NSIS installer runtime has its own applicable notices.

Pi Reader does not claim ownership of these third-party components. The MIT/ISC copyright and permission texts and font OFL originals are reproduced in licenses/. Pi Reader branding and artwork were created for this application.

## UnRAR and compiler runtime

node-unrar-js 2.0.2 includes UnRAR 6.1.7 compiled with Emscripten. The wrapper's MIT license does not replace the UnRAR license. Complete original terms are in licenses/UnRAR.txt, extracted from the exact upstream archive referenced by node-unrar-js: https://www.rarlab.com/rar/unrarsrc-6.1.7.tar.gz. UnRAR is free to use for reading RAR archives, including within commercial software, but its code cannot be used to create a RAR-compatible archiver or re-create the proprietary RAR compression algorithm. Pi Reader only extracts archives.

Emscripten generated runtime code retains its permissive MIT / University of Illinois-NCSA terms. The upstream license text is included as licenses/Emscripten.txt (https://github.com/emscripten-core/emscripten/blob/3.1.11/LICENSE); this license-text reference does not assert the compiler version used by the prebuilt node-unrar-js package. Electron's MIT license is also reproduced in licenses/Electron-MIT.txt.
