<a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=Yumi-Park996&utm_content=farm">
<img
  src="https://render.gitanimals.org/farms/Yumi-Park996"
  width="3000"
  height="600"
/>
</a>


# 🔱 Hello, I'm Yumi Park!

🌟 **A Developer in Progress**  
<br>
안녕하세요! 저는 백엔드 개발자가 되고 싶은 **AIBE 1기 학습자** 박유미입니다.  
<br>
현재 **Java와 JavaScript 기반의 백엔드 개발**을 공부하고 있으며,  
<br>
AI와 데이터 관련 기술에도 관심이 많아요.  

---

## 🚀 About Me
- 🔍 **현재 관심 분야**: 백엔드 개발 (Java & Node.js), AI 활용 서비스 개발
- 🎯 **배우고 있는 기술**: Java, JavaScript, Python, Node.js, Express.js, Supabase
- 🏆 **참여한 프로그램**: [Grep(Programmers) AIBE 1기](https://www.programmers.co.kr/)
- 💬 **협업을 원하는 분야**: AI 챗봇 개발, API 백엔드 구축, 데이터 엔지니어링
- 📩 **Contact**: byumm315@gmail.com

---

## 💻 My Projects

### 🦾 FixBot ([🔗FrontEnd-Repo](https://github.com/Yumi-Park996/FixBot-Frontend); [🔗BackEnd-Repo](https://github.com/Yumi-Park996/FixBot-Backend))_Now "MVP" Open! 🔥🔥🔥

> **사이드 프로젝트 - 증상 기반 고장 진단 챗봇** (React + Java SpringBoot + LLM)
- 사용자의 자연어 입력을 기반으로 전자제품의 고장 원인을 파악하고, AI가 적절한 해결책을 제시하는 챗봇
- 필요 시 검색어를 최적화하여 YouTube 및 Google API를 통해 실질적인 수리 영상을 제공
  
🔧 기술 스택
  
| 구분       | 사용 기술                                                                 |
|------------|--------------------------------------------------------------------------|
| Frontend   | React, CSS, Axios, Supabase (이미지 업로드용), Vite                      |
| Backend    | Java Spring Boot, OpenAI API, YouTube Data API, Google Search API       |
| AI 기술    | OpenAI GPT, Vision API (Gemini), 검색어 최적화 알고리즘 |
| 배포 환경  | Docker, Render (Frontend/Backend 각각 분리 배포)                         |

🔧 주요 기능

| 기능 구분             | 기능 설명                                                                                      |
|----------------------|-------------------------------------------------------------------------------------------------|
| 1. 대화형 고장 진단     | 사용자 입력을 분석하여 단계적으로 문제를 좁혀가며 고장 원인을 진단                                       |
| 2. 검색어 최적화        | OpenAI를 통해 사용자 문장을 검색 최적화 문장으로 변환<br>→ `##검색어: "..."` 형식으로 출력                  |
| 3. YouTube & Google 검색 | API를 활용해 적절한 콘텐츠를 필터링하여 사용자에게 추천                                                 |
| 4. AI 직접 해결책 제시   | 검색 기반이 아닌 AI가 직접 해결책을 생성 (RAG 미사용)                                                     |
| 5. 이미지 분석 기능     | 스크린샷 업로드 시 AI Vision 모델이 원인을 추정 (Supabase + Gemini Vision API 사용) |
| 6. 카테고리 기반 UX 흐름 | 브랜드 → 제품군 → 세부 증상 선택 구조 제공 (삼성, LG, Apple, Xiaomi 대응)                              |

---

### 🏆 PETTY ([🔗Repo](https://github.com/QuantumGuinea/FE-BASE))
> 팀 프로젝트 - 반려동물 동반 여행지 & 숙소 & 음식점 추천 웹서비스 (JavaScript, HTML, CSS)
- 주요 기능:
  - 🏨 반려동물 동반 여행지, 숙소, 음식점 추천 시스템 (LLM + RAG 활용 사용자 선호도 기반 장소 추천)
  - 📸 반려동물 이미지 기반 특징 분석지 생성 (WoW Moment 제공, Vision 모델 활용 반려동물 특성 분석기)
  - 📝 집사 커뮤니티 기능 (반려동물 관련 정보 작성 & 공유)
  - 🔐 로그인 & 회원가입 기능
- 기술 스택:
  - JavaScript (프론트엔드 로직 개발)
  - HTML, CSS (UI/UX 디자인)
  - GitHub Pages 배포
---

### 🏦 AIStockGuide ([🔗Repo](https://github.com/Yumi-Park996/Investment-guides))
> **사이드 프로젝트 - AI 기반 해외 주식 투자 가이드** (Java + OpenAI)
- 사용자의 질문을 분석하여 해외 주식 투자 관련 정보를 제공하는 AI 챗봇
- AI 기반 투자 상담: OpenAI API를 활용해 맞춤형 투자 가이드 생성
- 랜덤 투자 FAQ 제공: Supabase에서 투자 관련 FAQ 20개를 불러와 랜덤 노출
- YouTube 영상 추천: 해외 주식 관련 유튜브 영상 자동 추천
- Java 기반 백엔드 개발 및 Docker & Render로 배포 완료

### 📰 NewsBot_Renewal ([🔗Repo](https://github.com/Yumi-Park996/NewsBot_Renewal))
> **사이드 프로젝트 - 자동 뉴스 요약 & 투자자 코멘트 생성 봇** (Java + LLM)
- 최신 뉴스 수집 및 LLM 기반 요약, 투자자 코멘트 생성 자동화
- Naver 뉴스 API 크롤러 + Brevo 이메일 전송 기능 탑재
- GitHub Actions 스케줄러로 지정 시간마다 자동 실행
- 뉴스 수집부터 이메일 발송까지 원스톱 프로세스 구성
- Maven 프로젝트 + PowerShell 스크립트로 환경설정 자동화
---

## 📚 Learning Log (TIL)
💡 일별로 배운 것들을 정리한 TIL (Today I Learned)  
👉 [🔗TIL Repository](https://github.com/Yumi-Park996/TIL/issues)

---

## 📊 GitHub Stats
![Yumi-Park996's GitHub stats](https://github-readme-stats.vercel.app/api?username=Yumi-Park996&show_icons=true&theme=radical)  
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Yumi-Park996&layout=compact)](https://github.com/Yumi-Park996)  

---

## 💡 Let's Connect!
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/%EC%9C%A0%EB%AF%B8-%EB%B0%95-4a766828a/)  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat&logo=github)](https://github.com/Yumi-Park996)  
📧 Email: byumm315@gmail.com

---

✨ **"몰입하는 개발자, 박유미입니다"** ✨
