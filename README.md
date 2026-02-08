# Nuclear Option 한국어 패치 (Localization Patch)

Nuclear Option 게임의 한국어 번역 모드입니다. BepInEx 플러그인으로 동작하며, UI·백과사전·힌트·툴팁 등 **1,427개 항목**을 번역합니다.

## 요구사항

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Early Access 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## 설치 방법

1. **BepInEx 5.x**를 게임 폴더에 설치합니다.
   ```
   예: C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. 게임을 **한 번 실행**한 뒤 종료합니다. (BepInEx 폴더 구조가 생성됩니다)

3. 이 리포지토리의 모든 파일을 아래 경로에 복사합니다:
   ```
   [게임 폴더]\BepInEx\plugins\LocalizationPatch\
   ```
   > LocalizationPatch 폴더가 없으면 직접 만들어주세요.

4. 게임을 실행하면 **자동으로 한국어가 적용**됩니다.

## 포함된 파일

| 파일 | 설명 |
|------|------|
| `LocalizationPatch.dll` | 패치 플러그인 |
| `ko.json` | 한국어 번역 데이터 (1,427개 항목) |
| `Pretendard-Regular.otf` | 한글 표시용 폰트 |

## 인게임 단축키

| 키 | 기능 |
|----|------|
| `F10` | 디버그 오버레이 표시/숨기기 |
| `Ctrl+F10` | 번역 데이터 다시 불러오기 (핫 리로드) |

## 참고사항

- 미션 이름, 세력 이름(PALA, BDF)은 영어 그대로 유지됩니다.
- 문제 발생 시 `BepInEx\config\com.yuulf.localizationpatch.cfg` 파일에서 `Language = ko`로 직접 지정할 수 있습니다.

## 폰트 라이선스

Pretendard (v1.3.9) — [SIL Open Font License 1.1](https://github.com/orioncactus/pretendard)
