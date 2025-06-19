# 🗣️ 시선추적, 제스처 인식, STT 기반 AI 발표 트레이너 SPitching!

## 👩🏻‍💻 SPitching! Frontend

> AI 발표 트레이너 웹 프론트엔드 – 시선 추적, 제스처 분석, 발표 유창성 피드백까지! <br>
MediaRecorder 기반 발표 영상 녹화하고, AI 분석 결과를 차트로 시각화하여 보여주는 피드백 화면과 로그인 인증 흐름을 포함한 웹 인터페이스 구현
> 
> 
> `React + TypeScript + Tailwind CSS + Vite`
> 

## 🎯 **Project Goal**

발표에 대한 불안감을 극복하고 자신감을 높이기 위해

**시선, 제스처, 음성** 데이터를 분석한 종합 피드백을 제공하는 **AI 발표 연습 웹 애플리케이션**입니다.

- 시선추적, 제스처, 음성 기반 AI 분석 결과 시각화
- 대본과 실제 발표의 유사도 측정
- 반복 연습에 따른 발표력 향상률 제공
- AI 기반 Q&A 챗봇으로 질의응답 연습 가능

## 🧩 **Frontend Stack**

| **Category** | **Tech Stack** |
| --- | --- |
| **Framework** | React (with Vite) |
| **Language** | TypeScript |
| **Styling** | Tailwind CSS |
| **State Mgmt** | Redux Toolkit, React-Redux, redux-persist |
| **Data Fetching** | TanStack React Query |
| **Routing** | React Router DOM v7 |
| **Charting** | Recharts |
| **Icon** | lucide-react |
| **Lint/Format** | ESLint, Prettier |
| **Build Tool** | Vite |

## 📁 **Folder Structure**

```
src/
├── assets/           
├── 📂components/         # UI 컴포넌트
│   ├── common/         # 공통 UI (Button, Modal 등)
│   └── ...             # 페이지 별 UI
├── contexts/           # 컨텍스트
├── 📂pages/              # 라우팅되는 페이지
│   ├── landing/
│   ├── auth/
│   ├── dashboard/
│   ├── feedback/
│   ├── practice/
│   └── prep/
├── redux/              # 글로벌 상태 관리 (auth 등)
├── routes/           
├── services/           # API 호출 모듈
├── hooks/              # 커스텀 훅
├── types/              # TypeScript 타입 정의
└── utils/              # 유틸 함수

```

## 🚀 **Getting Started**

### 1. 설치 및 실행 (Local에서 실행하는 방법)

```bash
git clone https://github.com/2024-capstone-project/SPitching-FE.git
cd 폴더명
npm install
npm run dev
```

### 2. 환경 변수 설정

프로젝트 상단에  `.env` 파일을 생성하고, 아래 환경변수를 입력하세요 :

```
VITE_API_BASE_URL= 백엔드 API 요청 엔드포인트
VITE_AI_API_BASE_URL= AI 서버 API 요청 엔드포인트
```

---

## 🧪 **How to Test**

- 웹서비스 링크 / 로컬 링크로 접속하시면 됩니다.
- 구글 OAuth 및 세션 쿠키 사용을 통한 인증 방식이기 때문에 프론트만으로 전체 테스트는 어렵습니다.
- 반드시 백엔드와 함께 테스트해야 정상 작동합니다.
- 개발 단계에서는 백엔드가 로컬 혹은 EC2 상에 기동되어 있어야 합니다.

---

## 🔗 **Related Links**

- 🧠 [AI 서버 리드미](https://github.com/2024-capstone-project/SPitching-AI_SERVER.git)
- 🔐 [백엔드 리드미](https://github.com/2024-capstone-project/SPitching-BE.git)
- 📋 시제품 사용설명서 *(구현 후 링크 연결 예정)*

---
