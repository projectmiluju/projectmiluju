<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e293b&height=220&section=header&text=Archivist%20of%20Rare%20Stories&fontSize=42&fontColor=f8fafc&animation=fadeIn&fontAlignY=35&desc=드물지만%20드물지%20않은,%20그런%20이야기를%20코드로%20씁니다.&descAlignY=58&descSize=16" />
</p>

<p align="center">
  <a href="https://projectmiluju.github.io/">
    <img src="https://img.shields.io/badge/DevBlog-111827?style=for-the-badge&logo=githubpages&logoColor=white" />
  </a>
  <a href="mailto:project.miluju@gmail.com">
    <img src="https://img.shields.io/badge/Contact-4285F4?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<div align="center">
  <h3>🖋️ Web Service Planner & Full-stack Developer</h3>
  <p>기획의 <b>명확함</b>과 구현의 <b>완성도</b> 사이의 간극을 좁히는 것을 즐깁니다.<br/>
  단순한 기능을 넘어 사용자의 기억에 남는 시스템을 지향합니다.</p>
</div>

<br/>

## 🧭 Perspective
* **Architecture:** 서비스의 구조를 설계할 때 확장성과 안정성의 밸런스를 가장 중요하게 생각합니다.
* **Tech Blog:** [블로그](https://projectmiluju.github.io/blog/)를 통해 CS 지식, 서적 요약, 트러블슈팅을 기록하며 지식을 공유합니다.
* **Philosophy:** 코드는 드문 이야기를 담는 그릇이며, 그 그릇은 견고하고 아름다워야 한다고 믿습니다.

<br/>

## 🛠 Tech Stack

> **Core는 실전 구현 중심**, Used는 프로젝트에서 **직접 적용 경험**, Exploring은 **확장 학습 중**입니다.

### ✅ Core (제가 “끝까지 책임지고” 만들 수 있는 영역)
<p>
  <img src="https://img.shields.io/badge/Java-0f172a?style=flat-square&logo=openjdk&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Spring%20Boot-0f172a?style=flat-square&logo=springboot&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Spring%20Security%20%2B%20JWT-0f172a?style=flat-square&logo=springsecurity&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/JPA%20%2F%20Hibernate-0f172a?style=flat-square&logo=hibernate&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/QueryDSL-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/REST%20API-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/OpenAPI%20%2F%20Swagger-0f172a?style=flat-square&logo=swagger&logoColor=f8fafc" />
</p>

- **인증/인가:** Spring Security + JWT, reauthToken 기반 민감 작업 보호 흐름 설계/구현
- **API 설계:** 공통 응답 포맷(ApiResponseDto) · 예외 처리(GlobalException) · 문서화(Swagger) 정리
- **데이터 접근:** JPA → QueryDSL 전환, 필터/검색/페이징 구조화

---

### 🧱 Data · Search (설계/성능을 함께 보는 영역)
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-0f172a?style=flat-square&logo=postgresql&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/MySQL-0f172a?style=flat-square&logo=mysql&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/MariaDB-0f172a?style=flat-square&logo=mariadb&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Redis-0f172a?style=flat-square&logo=redis&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Elasticsearch-0f172a?style=flat-square&logo=elasticsearch&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/MongoDB-0f172a?style=flat-square&logo=mongodb&logoColor=f8fafc" />
</p>

- **관계형 중심 모델링:** 주문/상품/옵션 등 도메인 단위로 테이블·관계 구조화
- **검색:** Elasticsearch 기반 확장(필터/동의어/부분일치 등은 프로젝트 상황에 맞춰 적용)
- **캐시/토큰 저장:** Redis를 용도 분리(세션/토큰/실시간 협업 상태 등)

---

### 🎨 Frontend (UX를 “완성”으로 가져가는 영역)
<p>
  <img src="https://img.shields.io/badge/React-0f172a?style=flat-square&logo=react&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/TypeScript-0f172a?style=flat-square&logo=typescript&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/JavaScript-0f172a?style=flat-square&logo=javascript&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Vite-0f172a?style=flat-square&logo=vite&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/React%20Router-0f172a?style=flat-square&logo=reactrouter&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Zustand-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/SCSS-0f172a?style=flat-square&logo=sass&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Axios-0f172a?style=flat-square" />
</p>

- **상태 관리:** 전역 상태(Zustand) + API 연동 흐름 정리
- **구현:** 리스트/상세/무한스크롤/모달/관리자 테이블 등 실전 UI 패턴 구현

---

### ⚡ Realtime · Collaboration (WebIDE/실시간 경험 기반)
<p>
  <img src="https://img.shields.io/badge/WebSocket-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/STOMP-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Yjs-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Monaco%20Editor-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Socket.IO-0f172a?style=flat-square&logo=socketdotio&logoColor=f8fafc" />
</p>

- **협업 편집:** Yjs 자료구조(Y.Map 등)와 UI 컴포넌트 연결
- **실시간 통신:** STOMP/WebSocket 기반 이벤트 흐름 설계(채팅/알림/동기화 등)

---

### ☁️ DevOps · Infra (배포/운영까지 “내 손으로”)
<p>
  <img src="https://img.shields.io/badge/AWS-0f172a?style=flat-square&logo=amazonaws&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/EC2-0f172a?style=flat-square&logo=amazonec2&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/S3-0f172a?style=flat-square&logo=amazons3&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/RDS-0f172a?style=flat-square&logo=amazonrds&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/CloudFront-0f172a?style=flat-square&logo=amazoncloudfront&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Nginx-0f172a?style=flat-square&logo=nginx&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Docker-0f172a?style=flat-square&logo=docker&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-0f172a?style=flat-square&logo=githubactions&logoColor=f8fafc" />
</p>

- **CI/CD:** GitHub Actions로 배포 자동화 + 환경변수/스크립트 기반 운영
- **인프라:** EC2·S3·RDS·CloudFront 조합으로 실서비스 배포 경험, Nginx 리버스 프록시 구성

---

### 🧪 Testing · Quality · Tooling
<p>
  <img src="https://img.shields.io/badge/JUnit5-0f172a?style=flat-square&logo=junit5&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Mockito-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Git%20%2F%20GitHub%20Flow-0f172a?style=flat-square&logo=git&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Prettier%20%2F%20EditorConfig-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/IntelliJ%20IDEA-0f172a?style=flat-square&logo=intellijidea&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/VS%20Code-0f172a?style=flat-square&logo=visualstudiocode&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Figma-0f172a?style=flat-square&logo=figma&logoColor=f8fafc" />
</p>

---

### 🌱 Exploring (다음 스텝으로 확장 중)
<p>
  <img src="https://img.shields.io/badge/Kafka-0f172a?style=flat-square&logo=apachekafka&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Kubernetes-0f172a?style=flat-square&logo=kubernetes&logoColor=f8fafc" />
  <img src="https://img.shields.io/badge/Spring%20Batch-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/OpenTelemetry-0f172a?style=flat-square&logo=opentelemetry&logoColor=f8fafc" />
</p>

<br/>

## 🧩 Portfolio Showcase

| Project | Focus | Technical Strength | Link |
|:---|:---|:---|:---:|
| **Rare Storage** | 기획 & 인프라 설계 | **Spring Boot / S3 / RDS** | [View](https://github.com/projectmiluju) |
| **UX Archiving** | UI/UX & 상태관리 | **React / Framer Motion** | [View](https://github.com/projectmiluju) |
| **CI/CD Pipeline** | 배포 자동화 | **Github Actions / Docker** | [View](https://github.com/projectmiluju) |

<br/>

## 🏆 Growth Record

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=projectmiluju&theme=algolia&no-frame=true&no-bg=true&margin-w=4&column=4" alt="trophies" />
</p>

<br/>

## 📈 Activity Archive
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=projectmiluju&bg_color=0f172a&color=38bdf8&line=38bdf8&point=ffffff&area=true&hide_border=true&v=2" width="100%" />
</p>

<br/>

<div align="center">
  <p><sub>"I write rare stories in code, making the invisible visible."</sub></p>
  <a href="mailto:project.miluju@gmail.com"><img src="https://img.shields.io/badge/project.miluju@gmail.com-0f172a?style=flat-square&logo=gmail&logoColor=white"></a>
</div>
