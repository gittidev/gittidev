## 👋Boram

실시간 상호작용과 사용자 경험에 집중하는 프론트엔드 개발자입니다.  
WebSocket 기반의 실시간 통신 기능에 흥미를 느끼고 프로젝트에 적용해왔습니다.

---

### 🧠 About Me

- 🔭 삼성청년 SW 아카데미
- 📚 방송통신대학교 컴퓨터과학과 3학년 재학 중
- 🌱 주력 기술: `React.js`, `Next.js`, `TypeScript`, `FastAPI`, `Zustand`
- 📡 관심 분야: 실시간 서비스,WebSocket,VR
- 🧪 그외: `Supabase`, `Cloudflare`, `Docker`, `Electron`,
- 📫 Email: qhfka961@gmail.com  
- 📘 Portfolio: [miricanvas 보기](https://www.miricanvas.com/v/14exi21)  
- ✍️ Velog: [velog.io/@qhfka961](https://velog.io/@qhfka961/posts)
- 🪪 Licenses & Certifications : SQLD(SQL 개발자), 리눅스마스터 2급, 네이버 클라우드 플랫폼 Associate (NCA), 컴퓨터활용능력 1급

---

### 🧩 Real-time Projects

| 프로젝트명 | 설명 | 링크 |
|------------|------|------|
| **CRAM** | WebSocket 기반 실시간 CS 퀴즈 플랫폼 | [🔗 GitHub](https://github.com/CS-Quiz/CS-Quiz) · [🌐 배포](http://ec2-13-125-187-28.ap-northeast-2.compute.amazonaws.com/) |
| **대광PC** | Supabase 기반 건설현장 관리 및 메인 페이지 | [🔗 GitHub](https://github.com/gittidev/DK) · [🌐 배포](https://daekwang.site/) |
| **딸깍 (Ttalkak)** | Electron + Docker + WebSocket 기반 자동 배포 데스크탑 앱 | [🔗 GitHub](https://github.com/ttalkak) · [🌐 시연영상](https://drive.google.com/file/d/1js4fp3JqNJeQjxfPD53579oChui9PrTY/view?usp=drive_link) |
| **SroryBoat** | react flow를 사용한 실시간 협업 스토리텔링 플랫폼 | [🔗 GitHub](https://github.com/gittidev/Storyboat) · [🌐 시연영상](https://drive.google.com/file/d/1effF1OTSyWCgLvEwY9FcNvzh7E11mhiP/view?usp=drive_link) |



---

### 🛠️ Tech Stack

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,react,next,vue,fastapi,python,nodejs,docker,git,supabase,cloudflare,electron&perline=8" />
  </a>
</p>

---

### 📦 주요 경험 요약

- 🧵 WebSocket 모듈화 및 상태 관리: `useBattleSocket` 훅 + `Zustand`로 소켓 상태 동기화
- ⚙️ Pub/Sub 구조 설계: 서버와 클라이언트 간 주제 기반 실시간 메시지 전달
- ♻️ 소켓 재접속 / 세션 유지 처리: 새로고침 시 상태 복원 (`sessionStorage` 기반)

- 📡 **React Query 캐싱 전략 최적화**:
  - 불필요한 재요청 방지 (`staleTime`, `enabled`, `keepPreviousData`)
  - `useInfiniteQuery` 기반 무한스크롤 구현
  - WebSocket 수신 데이터와 Query 캐시 동기화
  - API와 UI 상태 분리 및 UX 개선

- 🔐 **JWT 기반 로그인 구현**:
  - Access / Refresh Token 분리 저장 (`httpOnly cookie` + `sessionStorage`)
  - 자동 로그인 / 토큰 만료 대응 리프레시 로직 직접 구성
  - 인증 상태를 Zustand + React Query로 전역 관리
  - API 요청 시 토큰 자동 주입 (Interceptor / Middleware 활용)

- 🔑 **OAuth 소셜 로그인 (Kakao, Naver 등)**:
  - 인가 코드 처리 → 백엔드 연동 후 JWT 발급 흐름 구축
  - 리다이렉트 이슈 및 CORS 대응 경험
  - 소셜 로그인 후 사용자 정보 동기화 (React Query + Zustand 연계)




<!--
**gittidev/gittidev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
