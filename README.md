# 📝 손글손수씨 (Son-Geul-Son-Su-Cci)
> **Upstage Solar & Document Parse를 활용한 "백지 복습" 자동 채점 AI 에이전트**

## 📌 프로젝트 소개
공부한 내용을 백지에 써서 업로드하면, AI가 교안 및 필기 내용과 비교하여 자동으로 채점하고 피드백을 주는 **AI 튜터 에이전트**입니다.

## 🛠 사용 도구 (Tech Stack)
- **Workflow Tool**: n8n
- **Vision AI**: Upstage Document Parse (OCR)
- **Brain AI**: Upstage Solar Pro (LLM)
- **Database**: Google Drive & Google Docs

## 📂 파일 구성
- `Upstage-AI-Tutor-Agent.json`: n8n 워크플로우 전체 JSON 코드 파일입니다.

## 🚀 사용 방법 (How to use)
1. 위 `손글손수씨ver3.json` 파일을 다운로드하거나 내용을 복사합니다.
2. 본인의 n8n 캔버스에서 `Ctrl + V` (붙여넣기)를 하거나, 'Import from File' 기능을 사용합니다.
3. Google Drive 및 Upstage API Credential을 본인의 것으로 설정합니다.
4. Workflow를 활성화(Active)하면 바로 사용할 수 있습니다.
