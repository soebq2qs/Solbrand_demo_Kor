# Solbrand Demo (솔브랜드)한글패치 v0.8 (비공식, 2026-10-30)

Steam판 **Solbrand Demo**의 대사·문서·UI를 한국어로 바꾸는 비공식 팬 패치입니다.

> 맞는 게임 버전: **2026-10-31 Steam 업데이트본**. 게임이 다시 업데이트되면 패처가 아무것도 바꾸지 않고 멈춥니다. 그때는 새 패치를 받아 주세요.

Releases
탭 에서 받아가시면 됩니다

## 설치

1. 아래 **Assets**에서 `SolbrandKR_20261030f.zip`을 받아 압축을 풉니다.
2. 게임을 끕니다.
3. `SolbrandKR_patcher.exe`를 실행합니다. **"완료!"** 가 나오면 끝입니다.
   - 예전 한글패치가 깔려 있어도 그대로 실행하면 새 버전으로 바뀝니다.
   - **"게임 폴더를 찾지 못했습니다"** 가 나오면: 압축을 푼 `SolbrandKR` 폴더를 통째로 게임 폴더에 넣고 다시 실행하세요.
     (Steam → Solbrand Demo 우클릭 → 관리 → 로컬 파일 보기)

## 제거

- `한글패치_제거.bat`을 실행하면 원래(영어) 상태로 돌아갑니다.
- 게임 폴더의 `Solbrand.pck.kobak`, `Solbrand.dll.kobak`은 제거할 때 필요하니 지우지 마세요.
- Steam의 **게임 파일 무결성 검사**로도 원래대로 돌아갑니다.

## 번역 범위

**한국어로 바뀐 것**
- 대사(Ink), 게임 데이터 문자열, 메뉴·UI 대부분
- ARKIV 단서 그림 14장의 그림 속 글자: 은어 사전 3쪽, 새끼손가락 쪽지, 작업 주문서, 코스 지도 2장, UVC 전보, 영수증, 서커스 표, 그을린 사진, 사라진 칸 도면, 08단 전단, 소변기 시
  - 퍼즐 기호·숫자·스웨덴어·서명은 원본 그대로 두었습니다.

**일부러 원문 그대로 둔 것**
- 스웨덴어 지명·라벨 (원작 의도)
- 룬으로 뒤섞이는 글자
- '오딘의 눈'으로 볼 때만 나타나는 내용 (서커스 표의 스웨덴어 문구, 사진의 말 등)
- 혜성 배지 구호 (그림은 영어 그대로, 설명 칸에 한글 뜻을 적음)
- 그 밖의 그림 속 글자: 버튼·손글씨 테이프 그림, 신호기 팸플릿, 매듭 개론 (풀이에 필요한 글자는 그대로 읽힘)
- 단위·약어 (Hz, BAR/KPA 등)

## 알아 두실 점

- 패치 전에 영어로 플레이한 세이브는 그때 쌓인 **LOGG 기록·ARKIV 기록 쪽지가 영어로 남습니다.** 패치 뒤에 새로 쌓이는 기록은 한글로 나옵니다.
- 시험판입니다. 오역·깨진 글자·영어로 남은 곳을 찾으시면 [Issues](../../issues)에 스크린샷과 함께 남겨 주세요.

## 글꼴 · 라이선스

한글 표시에 아래 글꼴을 고쳐(필요한 글자만 남기고 이름을 바꿈) 넣었습니다. 모두 **SIL Open Font License 1.1**이며, 전문은 zip 안 `OFL` 폴더에 있습니다.

- 나눔고딕코딩, 나눔손글씨 펜 (NAVER): 이름을 `SolbrandKR NG…`로 바꿈
- 개구, 고딕 A1, 송명

---

이 패치는 비공식 팬 번역이며 개발사·배급사와 관계가 없습니다. 원작의 권리는 원저작자에게 있습니다.

---

## English

Unofficial fan-made **Korean translation patch** for **Solbrand Demo** (Steam).

> Compatible game version: **Steam update of 2026-10-30**. If the game updates again, the patcher stops without changing anything. Please wait for a new patch.

### Install

1. Download `SolbrandKR_20261030f.zip` from **Assets** below and extract it.
2. Close the game.
3. Run `SolbrandKR_patcher.exe`. It's done when it shows **"완료!"** ("Done!").
   - If an older version of the patch is installed, just run the new patcher. It updates in place.
   - If it says **"게임 폴더를 찾지 못했습니다"** ("Game folder not found"): move the whole `SolbrandKR` folder into the game folder and run it again.
     (Steam → right-click Solbrand Demo → Manage → Browse local files)

### Uninstall

- Run `한글패치_제거.bat`. The game returns to its original (English) state.
- Do not delete `Solbrand.pck.kobak` and `Solbrand.dll.kobak` in the game folder. They are needed to uninstall.
- Steam's **Verify integrity of game files** also restores the original.

### What is translated

- Dialogue (Ink), game data strings, and most menus/UI
- Text inside 14 ARKIV clue images, redrawn in Korean. Puzzle symbols, numbers, Swedish text, and signatures are kept as in the original.

**Intentionally left as is:** Swedish place names and labels (original intent), rune-scrambled text, content visible only through "Odin's Eye", the comet badge slogan (Korean meaning added to its description), some other in-image text (buttons, handwritten tape images, signal pamphlet, knot primer), and units/abbreviations (Hz, BAR/KPA, etc.).

### Notes

- In saves played in English before patching, existing LOGG entries and ARKIV notes stay in English. New entries after patching appear in Korean.
- This is a test release. Please report mistranslations, broken characters, or leftover English in [Issues](../../issues) with a screenshot.

### Fonts & license

Nanum Gothic Coding and Nanum Pen Script (NAVER), Gaegu, Gothic A1, and Song Myung are included in modified form (subset and renamed; the NAVER fonts as `SolbrandKR NG…`). All are under the **SIL Open Font License 1.1**; full texts are in the `OFL` folder in the zip.

This is an unofficial fan translation and is not affiliated with the developer or publisher. All rights to the original game belong to their respective owners.
