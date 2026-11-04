<div align="center">

![RunStop 모바일 앱, Node.js API, FastAPI Worker, PostGIS 구성도](assets/profile-hero.svg)

# 문제를 구조로 이해하고, 코드로 검증합니다.

안녕하세요. 개발자 **허완**입니다. 백엔드와 데이터 기반 서비스를 구현하며, 설계한 시스템이 실제로 어떻게 동작하는지 확인하는 과정을 중요하게 생각합니다.

**Backend · AI/ML · Engineering**

[프로젝트 보기](#selected-work) · [포트폴리오](https://app.notion.com/p/1be117a41d4d80feae10fe11f2262b54) · [기술 블로그](https://hurwan.tistory.com)

</div>

---

<table>
<tr>
<td width="33%" align="center"><img src="assets/icon-backend.svg" width="52" alt=""/><br><strong>Backend</strong><br><sub>API · 데이터 흐름</sub></td>
<td width="33%" align="center"><img src="assets/icon-ai.svg" width="52" alt=""/><br><strong>AI / ML</strong><br><sub>추천 · 강화학습</sub></td>
<td width="33%" align="center"><img src="assets/icon-docs.svg" width="52" alt=""/><br><strong>Build & Docs</strong><br><sub>구현 · 검증 · 기록</sub></td>
</tr>
</table>

## Selected work

### 01 / RunStop

<table width="100%"><tr><td width="100%">
<h4>러닝 코스 추천 서비스</h4>
<p><strong>2026.08.23 – 2026.09.20 · 팀 프로젝트</strong></p>
<p>거리, 경사, 주변 시설과 시간 정보를 고려해 러닝 코스를 제안합니다. 모바일 앱, Node.js API, FastAPI Worker와 PostgreSQL/PostGIS를 연결했습니다.</p>
<p>참여자 기록에 따르면 <strong>서비스 아키텍처·DB·서버 설계, 프로젝트 문서화, AI 추천 모델</strong> 작업에 참여했습니다.</p>
<p><code>Node.js</code> <code>FastAPI</code> <code>PostgreSQL / PostGIS</code> <code>Docker</code></p>
<p align="center">
<img src="https://raw.githubusercontent.com/hurwan0629/RunStop/main/assets/service-screenshot/9.jpg" width="29%" alt="RunStop 추천 코스 비교 화면">
<img src="https://raw.githubusercontent.com/hurwan0629/RunStop/main/assets/service-screenshot/11.jpg" width="29%" alt="RunStop 코스 상세 지도 화면">
<img src="https://raw.githubusercontent.com/hurwan0629/RunStop/main/assets/service-screenshot/12.jpg" width="29%" alt="RunStop 실시간 러닝 화면">
</p>
<p align="center"><sub>코스 비교 · 상세 지도 · 실시간 러닝</sub></p>
<p><a href="https://github.com/hurwan0629/RunStop">코드와 README →</a> · <a href="https://app.notion.com/p/93c4bef3cd8549f3b84e0801bbb43b8b">설계 및 개발 기록 →</a></p>
</td></tr></table>

### 02 / Space Z

<table width="100%"><tr><td width="100%">
<h4>게임과 강화학습 실험</h4>
<p>Python/Pygame 게임을 강화학습 환경과 연결하고 PPO 학습을 실험한 팀 프로젝트입니다.</p>
<p><code>Python</code> <code>Pygame</code> <code>PyTorch</code> <code>Gymnasium</code> <code>Stable-Baselines3</code></p>
<p align="center"><img src="assets/space-z-cover.png" width="620" alt="Space Z 프로젝트 Notion 대표 이미지"></p>
<p align="center"><sub>프로젝트 Notion 대표 이미지</sub></p>
<p><a href="https://github.com/hurwan0629/kdt-final-3-space-z">코드와 README →</a> · <a href="https://github.com/hurwan0629/kdt-final-3-space-z/blob/main/src/space_z/rl/README.md">강화학습 환경 문서 →</a> · <a href="https://github.com/hurwan0629/kdt-final-3-space-z/blob/main/assets/img/rotation_continuous/visual_selected_seed51001__step_012000.png">실제 플레이 화면 →</a> · <a href="https://app.notion.com/p/3f7117a41d4d80c7920bc9feaf56b1ea">프로젝트 기록 →</a></p>
</td></tr></table>

### 03 / Ornably

<table width="100%"><tr><td width="100%">
<h4>쇼핑몰 웹 서비스</h4>
<p><strong>2025.11.19 – 2026.01.08 · 4명 팀 프로젝트</strong></p>
<p>로그인, 상품, 주문, 결제 흐름을 구현하며 웹 서비스의 구조를 학습한 프로젝트입니다. 저장소의 구현은 Java Servlet/JSP, JDBC, Oracle 기반입니다.</p>
<p><code>Java</code> <code>Servlet / JSP</code> <code>JDBC</code> <code>Oracle</code></p>
<p align="center"><img src="assets/ornably-site.jpeg" width="260" alt="Ornably 웹 사이트의 크리스마스 오너먼트 상품 상세 페이지"></p>
<p align="center"><sub>실제 상품 상세 페이지 화면 · 허완 포트폴리오 자료</sub></p>
<p><a href="https://github.com/hurwan0629/BugSandwichOrnamentMall">코드와 README →</a> · <a href="https://github.com/hurwan0629/BugSandwichOrnamentMall/blob/main/src/main/webapp/ornamentDetailPage.jsp">상품 상세 페이지 소스 →</a> · <a href="https://app.notion.com/p/2e3117a41d4d8048b1a6dda54bb58bc1">프로젝트 문서 →</a></p>
</td></tr></table>

---

## 개발 접근 방식

1. 요구사항과 데이터 흐름을 먼저 정리합니다.
2. 구현한 기능을 실제 사용 흐름에서 확인합니다.
3. 실험 과정과 설계 판단을 문서로 남깁니다.

## 사용한 기술

| 영역 | 프로젝트에서 사용한 기술 |
| --- | --- |
| Backend | Java, Servlet/JSP, Node.js, FastAPI |
| Data & AI | PostgreSQL/PostGIS, Oracle, Python, PyTorch, Gymnasium |
| Tools | Docker, GitHub |

---

<div align="center">

**기록과 코드 더 보기**

[포트폴리오](https://app.notion.com/p/1be117a41d4d80feae10fe11f2262b54) · [기술 블로그](https://hurwan.tistory.com) · [GitHub](https://github.com/hurwan0629)

</div>
