# 📦 AI Smart Archive (스마트 북마크 & AI 프롬프트 보관소)

> **호더(Hoarder)** 스타일의 AI 기반 스마트 북마크 및 프롬프트 통합 보관소 웹앱입니다.
> 텔레그램 AI 비서봇(`04_AI비서` / `my_personal_seol759_bot`)과 실시간으로 연동되어, 스레드(Threads), 구글 검색, SNS에서 발견한 유용한 프롬프트와 링크를 복사·붙여넣기만 하면 Gemini AI가 자동으로 요약·분류·키워드 태깅하여 영구 보관합니다.

---

## 🌟 주요 기능

### 1. ✨ AI 프롬프트 보관소 (Prompt Vault)
- 📋 **간편 붙여넣기 등록**: 스레드, 구글 검색, X(Twitter)에서 발견한 유용한 프롬프트 원문을 복사해 붙여넣으면 즉시 저장.
- 🤖 **Gemini AI 자동 분석 & 3줄 요약**: 프롬프트의 목적, 활용 상황, 기대 산출물을 3개의 불릿 포인트로 자동 요약.
- 🏷️ **자동 카테고리 & 키워드 태깅**: 글쓰기/창작, 코딩/개발, 마케팅/SNS, 이미지 생성 등 8대 카테고리 분류 및 관련 해시태그 5개 자동 추출.
- 🛠️ **추천 AI 모델 자동 감지**: ChatGPT (GPT-4o), Claude 3.5 Sonnet, Gemini 2.0, Midjourney v6 등 최적 모델 추천.
- 📋 **원클릭 클립보드 복사**: 카드에서 즉시 프롬프트 원문을 복사하여 ChatGPT나 Claude에 즉각 활용.
- 🔍 **실시간 전문 검색 & 필터링**: 제목, 요약, 태그, 모델, 원문 전체를 대상으로 즉각적인 실시간 검색.

### 2. 🗂️ 킵리아 인벤토리 (Keeplea Vault)
- 📷 **카메라 촬영 & 0.05초 초고속 압축**: 가전제품 모델명 라벨, 공유기 라벨, 영수증, 물건을 촬영하면 0.05초 만에 초고속 압축 및 AI 분석.
- 📄 **PDF / 전자문서 / CSV 메타데이터 추출**: 사용설명서, 계약서, 영수증 PDF 업로드 시 AI 정독 및 주요 조항/만기일 요약.
- 🎙️ **음성 메모 & 통화 녹음 자동 전사**: 음성 오디오 업로드 시 텍스트 받아쓰기 및 핵심 할일(To-Do) 자동 정리.
- 📶 **와이파이 QR 코드 원클릭 생성**: 공유기 라벨 인식 시 SSID/비밀번호 자동 추출 및 손님용 원클릭 와이파이 접속 QR 코드 팝업 제공.

### 3. 📦 스마트 북마크 아카이브
- 📱 **텔레그램 봇 실시간 연동**: 링크(뉴스, 릴스, 유튜브, IT 기술 블로그) 전송 시 AI가 자동 분석 후 `[✅ 아카이브에 저장]` 인라인 승인 버튼 제공.
- 🎨 **핀터레스트/호더 스타일 Masonry 카드 뷰**: 썸네일, 파비콘, 도메인 뱃지, 3줄 AI 요약 불릿, 해시태그 칩, 반응형 다단 레이아웃.
- 🌓 **다크 모드 / 라이트 모드**: 사용자의 시스템 설정 또는 수동 전환 지원 (영구 저장).
- 📌 **즐겨찾기(Pin) & 읽음(Read) 관리**: 0ms 낙관적 UI 업데이트(Optimistic UI) 및 구글 시트 클라우드 DB 영구 동기화.

---

## 🤖 텔레그램 AI 비서 연동 (`my_personal_seol759_bot`)

- 하단 고정 키보드 탭: `[✨ 프롬프트 아카이브]`, `[🎾 테니스일지]`, `[🗂️ 킵리아 보관소]`, `[📦 스마트 북마크]`
- 대화방 좌측 하단 메인 메뉴 버튼: `[🎾 테니스일지]` 100% 보존 유지
- 채팅창에 프롬프트 텍스트를 전송하면 AI가 자동 감지하여 요약 및 보관 안내

---

## 🌐 라이브 웹앱 주소

- **스마트 아카이브 메인**: [https://mi2tall-commits.github.io/smart-archive-app/](https://mi2tall-commits.github.io/smart-archive-app/)
- **✨ 프롬프트 보관소 탭**: [https://mi2tall-commits.github.io/smart-archive-app/?tab=prompt](https://mi2tall-commits.github.io/smart-archive-app/?tab=prompt)
- **🗂️ 킵리아 인벤토리 탭**: [https://mi2tall-commits.github.io/smart-archive-app/?tab=keeplea](https://mi2tall-commits.github.io/smart-archive-app/?tab=keeplea)
- **백엔드 클라우드**: Google Apps Script & Google Spreadsheet DB

