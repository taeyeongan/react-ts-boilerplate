# React + TypeScript Boilerplate

Vite, React, TypeScript, Zustand, Emotion, MUI, Tailwind CSS를 사용하여 구성된 프론트엔드 보일러플레이트입니다.

## 주요 기술 스택

*   **프레임워크**: React
*   **언어**: TypeScript
*   **빌드 도구**: Vite
*   **상태 관리**: Zustand
*   **스타일링**:
    *   Emotion & MUI
    *   Tailwind CSS
*   **린팅 & 포맷팅**: ESLint & Prettier

## 프로젝트 구조

```
my-react-app/
├── public/
├── src/
│   ├── api/             # API 호출 함수
│   ├── assets/          # 이미지, 폰트 등
│   ├── components/      # 재사용 가능한 공통 컴포넌트
│   │   ├── common/        # Button, Input 등 원자 단위
│   │   └── layout/        # Header, Footer, Sidebar 등
│   ├── constants/       # 전역 상수
│   ├── hooks/           # 커스텀 훅
│   ├── pages/           # 페이지 단위 컴포넌트
│   ├── store/           # Zustand 스토어
│   ├── styles/          # 전역 스타일, 테마 등
│   ├── types/           # 공통 타입 정의
│   ├── utils/           # 유틸리티 함수
│   ├── App.tsx          # 메인 앱 컴포넌트
│   └── main.tsx         # 애플리케이션 진입점
├── .eslintrc.cjs
├── .prettierrc
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── tsconfig.json
```

## 사용 가능한 스크립트

*   `yarn dev`: 개발 모드로 Vite 서버를 실행합니다.
*   `yarn build`: 프로덕션용으로 프로젝트를 빌드합니다.
*   `yarn lint`: ESLint를 사용하여 코드 스타일을 검사합니다.
*   `yarn preview`: 빌드된 결과물을 미리 봅니다.
*   `yarn format`: Prettier를 사용하여 코드 서식을 맞춥니다.
