# English Tutor

스마트폰에서 URL로 여는 1:1 AI 영어 과외 선생님 (Claude Opus 5.5).

- 수업 시작 → 복습 퀴즈 3개(첫 수업은 레벨 체크) → 문장 교정 → 재시도 반복
- 틀린 문장을 **오답노트**에 자동 기록하고, 다음 수업 복습 퀴즈에 다시 출제
- 복습에서 2번 연속 맞히면 "졸업"
- "오늘 수업 끝" → 배운 것 / 약점 / 숙제 저장
- 🎤 음성 입력(EN/KO 전환), 🔊 영어 문장 듣기

## 사용법

1. GitHub Pages로 배포: Settings → Pages → Branch `main` / `/ (root)` → Save
2. 폰에서 `https://danny-hub250.github.io/ai-translator/` 열기 → 공유 → **홈 화면에 추가**
3. ⚙︎ 설정에 Claude API 키 입력 ([console.anthropic.com](https://console.anthropic.com/settings/keys))

## 데이터

- API 키, 오답노트, 수업 기록은 모두 **그 기기의 브라우저(localStorage)** 에만 저장됩니다. 코드에는 키가 없습니다.
- 다른 기기로 옮기려면 오답노트 → 내보내기/가져오기.
- 콘솔에서 월 사용 한도(spend limit)를 설정해 두는 것을 권장합니다.
