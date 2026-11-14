# HiBro Sheets

HiBro Sheets is an independently installable HiBro editor. The unified Office app and a separate Python installation are not required.

[Downloads and Korean installation guide](https://hibro-office-download.jsyoon6532.chatgpt.site/download/#individual)

| System | Installer 0.8.59 |
| --- | --- |
| Mac · Apple Silicon | [Download](https://github.com/sungyoon-j/hibro-sheets-downloads/releases/download/v0.8.59/HiBro-Sheets-0.8.59-mac-arm64.dmg) |
| Mac · Intel | [Download](https://github.com/sungyoon-j/hibro-sheets-downloads/releases/download/v0.8.59/HiBro-Sheets-0.8.59-mac-x64.dmg) |
| Windows x64 · unsigned preview | [Download](https://github.com/sungyoon-j/hibro-sheets-downloads/releases/download/v0.8.59/HiBro-Sheets-0.8.59-win-x64.exe) |

Mac requires macOS 13 or later. Mac installers are signed and notarized. Basic editing and file saving work without an account. Each app has its own local workspace and automatic update channel. Open existing documents through File Open. The unified HiBro Office app can remain installed. New updates are downloaded automatically and applied after documents are saved and the app quits normally.

Windows installers are unsigned previews. Hosted Windows tests cover installation, physical file editing/saving/reopening, and real public-feed updates. Verification on an ordinary physical Windows PC remains outstanding. Optional online vault login is not verified while the existing service is paused.
## 0.8.59 변경 사항

글자 사이에 들어간 그림의 순서가 DOCX 수정·저장 후에도 유지되도록 고쳤습니다. 엑셀의 음수·거듭제곱 계산 순서와 SUM·COUNT·COUNTA의 직접 입력값·참조 셀·빈 문자열·오류 집계를 수정했습니다. 실제 설치 앱의 Mac 화면 검사와 Mac·Windows 내장 처리 도구의 DOCX·XLSX 저장·재열기를 확인했습니다. 기존 사용자는 문서를 저장한 뒤 앱을 정상 종료하면 자동으로 내려받은 업데이트가 적용됩니다.

## 0.8.58 변경 사항

저장과 다른 이름으로 저장을 별도 아이콘으로 제공하고, 파일 메뉴·리본·단축키를 정리했습니다. 기존 파일 열기는 실제 저장 위치에 연결되며, 사본은 다른 이름으로 저장해 별도로 편집할 수 있습니다. Mac 앱은 서명·공증을 마쳤습니다. Windows 설치 파일은 서명 전 시험판이며 일반 PC 검증은 별도입니다.

## 0.8.57 print layout

Preserves percentage printing versus fit-to-pages, original margins, print area and manual page breaks. Page Layout offers explicit percentage, one-page, width/height and custom page counts. Long sheets remain multipage when requested. Files whose print mode was already overwritten by an older app need the desired mode selected again.

PDF/ODF conversion requires LibreOffice installed on the computer. Basic editing and saving do not require it or an account.
