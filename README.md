# 안녕하세요! 👋 김승대입니다

**15년차 시니어 프론트엔드 개발자**로 사용자 경험을 최우선으로 하는 웹 서비스를 만들어가고 있습니다.
최근에는 **브라우저에서 동작하는 온디바이스 AI**와 **프라이버시 퍼스트 에듀테크**에 집중하고 있습니다.

## 🚀 About Me

```typescript
const KimSeungDae = {
  role: "Senior Frontend Developer",
  experience: "15+ years",
  location: "Seoul, South Korea",
  currentFocus: ["On-device AI", "EdTech", "Privacy-first", "TypeScript"],
  passion:
    "Building AI-powered tools that run 100% in the browser — no data leaves the device",
};
```

- 💼 **현재**: 동아출판 플랫폼서비스개발 과장
- 🎯 **전문 분야**: 프론트엔드 아키텍처 설계, 팀 리딩, 성능 최적화
- 🔬 **현재 관심사**: ONNX/MediaPipe 브라우저 추론, Web Worker, WASM
- 💬 **대화 주제**: React, Vue.js, On-device ML, 팀 빌딩
- 📫 **연락처**: kocacolla@naver.com

## 🌟 Featured Projects — EdTech × On-device AI

> 서버에 데이터를 보내지 않는, 100% 클라이언트사이드 AI 교육 도구

### 🖊️ [ink-on](https://github.com/kimseungdae/ink-on) — 손글씨 수학 인식

> **npm**: [`ink-on`](https://www.npmjs.com/package/ink-on) · **Demo**: [ink-on.vercel.app](https://ink-on.vercel.app)

브라우저에서 손글씨 수학식을 실시간으로 인식합니다. CoMER 모델을 ONNX INT8(7.2MB)로 변환하여 Web Worker에서 추론하며, LaTeX 자동 수정 + KaTeX 검증까지 클라이언트에서 완결됩니다.

- 🧠 ONNX Runtime Web + Web Worker 비동기 추론
- ✏️ 캔버스 기반 잉크 입력 → LaTeX → 수식 렌더링
- 📦 npm 라이브러리 (framework-agnostic core + Vue 바인딩)
- 🔒 100% 클라이언트사이드 — 서버 전송 없음

### 👁️ [sense-on](https://github.com/kimseungdae/sense-on) — 실시간 주의력 감지

> **npm**: [`sense-on`](https://www.npmjs.com/package/sense-on) · **Demo**: [sense-on.vercel.app](https://sense-on.vercel.app)

카메라로 학생의 주의력 상태를 실시간 감지합니다. MediaPipe Face Landmarker로 468개 얼굴 랜드마크를 추적하고, 머리 자세(Yaw/Pitch/Roll) + 눈 개폐(EAR)로 4단계 상태를 판정합니다.

- 🎯 4단계 상태: 집중 / 딴 곳 보기 / 졸음 / 자리비움
- 📊 One-Euro Filter 기반 안정적 추적 + 실시간 대시보드
- 📱 PC / Android / iPad 크로스 브라우저 지원
- 🔒 카메라 데이터가 브라우저를 떠나지 않음

### 📐 [step-on](https://github.com/kimseungdae/step-on) — 세로셈 애니메이션 _(개발 중)_

> **npm**: [`step-on`](https://www.npmjs.com/package/step-on) · **Demo**: [step-on-math.vercel.app](https://step-on-math.vercel.app)

초등 수학 세로셈 풀이 과정을 단계별 Lottie 애니메이션으로 생성합니다. DSL 아키텍처로 사칙연산의 풀이 과정을 컴파일하고, TTS 음성 안내까지 제공합니다.

- 🎬 Compiler → Step[] DSL → Renderer → Lottie JSON
- 🔊 단계별 TTS 음성 안내 (Web Speech API)
- ➕➖✖️➗ 사칙연산 지원, 28개 atomic action 타입

## 🛠️ Tech Stack

### **Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)

### **AI / ML on Browser**

![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white)
![Web Workers](https://img.shields.io/badge/Web_Workers-FF6F00?style=for-the-badge&logo=javascript&logoColor=white)

### **Styling & Tools**

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 🏆 Career Highlights

### 💼 **주요 프로젝트**

- 🏫 **AI 디지털 교과서** - Next.js, MonoRepo 구조 설계 (웅진씽크빅)
- 📱 **Lounge App** - React, D3.js 데이터 시각화 (웅진씽크빅)
- 🛠️ **문항 저작 도구** - Electron, React 데스크톱 앱 (웅진씽크빅)
- 🌐 **CJ 계열사 웹사이트** - 웹표준, 접근성 준수 개발 (CJ헬로비전)

### 🎯 **주요 성과**

- **MonoRepo 아키텍처** 설계로 교사/학생 서비스 통합 개발
- **CI/CD 파이프라인** 구축으로 배포 효율성 향상
- **15년+ 실무 경험**으로 다양한 도메인 프로젝트 리딩
- **팀 멘토링**을 통한 주니어 개발자 성장 지원

## 📚 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->

- [typescript 의 ANY사용에 설계 타협점](https://velog.io/@bambam/typescript-%EC%9D%98-ANY%EC%82%AC%EC%9A%A9%EC%97%90-%EC%84%A4%EA%B3%84-%ED%83%80%ED%98%91%EC%A0%90)
- [마이크로프론트엔드 아키텍처](https://velog.io/@bambam/%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-2024-2025)
<!-- BLOG-POST-LIST:END -->

## 🤝 Connect with Me

<div align="center">

[![Velog](https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/@bambam/posts)

</div>

## 💡 Fun Facts

- 🎮 게임 개발 교육 이수 (멀티플랫폼 게임제작전문가)
- 🤖 2006년 국제로봇올림피아드 청소로봇 대회 3위 수상
- 📝 웹 접근성과 웹 표준을 준수하는 개발을 지향
- 🌱 지속적인 학습과 새로운 기술 도입에 열정적

---

<div align="center">

**"좋은 코드는 혼자가 아닌 팀과 함께 만들어갑니다"**

![Visitor Count](https://profile-counter.glitch.me/kimseungdae/count.svg)

</div>
