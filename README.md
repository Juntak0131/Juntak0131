<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=HAN%20JUNTAK&fontSize=70&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Build%20%C2%B7%20Secure%20%C2%B7%20Ship&descSize=20&descAlignY=58" width="100%" />

<img src="https://img.shields.io/badge/Dongyang%20Mirae%20Univ.-203A43?style=flat-square" />
<img src="https://img.shields.io/badge/Computer%20Software%20Eng.-2C5364?style=flat-square&logo=gitbook&logoColor=white" />

</div>

<br/>

## 👨🏻‍💻 About Me

> **"돌아가는 데서 멈추지 않고, 믿고 쓸 수 있을 때까지 만듭니다."**

동양미래대학교 **컴퓨터소프트웨어공학과**에서 서버와 AI 서비스를 중심으로 공부하고 있습니다.
졸업작품 **UPM**에서는 FastAPI 기반 서버 파트를 맡았고, **Spring Boot** 자산 관리 대시보드는 JWT 인증부터 클라우드 배포까지 직접 해 봤습니다.
**OpenAI API**로는 정답 유출을 구조적으로 막는 AI 추리 게임을 만들었습니다.
기능 구현에서 끝내지 않고 **보안 · 테스트 · 배포**까지 책임지는 것을 중요하게 생각합니다.

<br/>

## 🛠️ Tech Stack

<div align="center">
<table>
  <tr>
    <td align="center" width="140"><b>Server</b></td>
    <td><img src="https://skillicons.dev/icons?i=java,spring,python,fastapi,mysql" height="44" /></td>
  </tr>
  <tr>
    <td align="center"><b>Web</b></td>
    <td><img src="https://skillicons.dev/icons?i=react,vite,js,html,css" height="44" /></td>
  </tr>
  <tr>
    <td align="center"><b>Infra & Tools</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,vercel,git,github" height="44" /></td>
  </tr>
  <tr>
    <td align="center"><b>More</b></td>
    <td>
      <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" />
      <img src="https://img.shields.io/badge/Face%2B%2B%20API-1E90FF?style=for-the-badge" />
      <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
      <img src="https://img.shields.io/badge/Apache%20Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" />
      <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" />
    </td>
  </tr>
</table>
</div>

<br/>

## 🚀 Key Projects

<table>
  <!-- ───────── UPM (졸업작품) ───────── -->
  <tr>
    <td colspan="2" valign="top">
      <h3>🎓 <a href="https://github.com/DMU-DeCode/upm-server">UPM — Universal PC Manager</a></h3>
      <b>PC 하드웨어 실시간 모니터링 · 원격 최적화 시스템</b><br/>
      <sub>졸업작품 · DMU-DeCode 팀 · 서버 파트 (Tier 2) 담당</sub>
      <ul>
        <li>C# 에이전트(Client) — <b>FastAPI 서버</b> — 웹/모바일 대시보드로 이어지는 <b>3-Tier 구조</b>의 서버 파트</li>
        <li>CPU · RAM · GPU 텔레메트리를 비동기로 수신해 <b>MySQL 시계열 로그</b>로 적재, <b>Pydantic v2</b>로 비정상 패킷 차단</li>
        <li><b>Smart Cleanup</b> — 창 유무 · CPU 유휴 · 메모리를 종합해 종료 대상을 판정하고, 시스템 · 개발 도구 · 사용자 예외 · 서버 자신을 지키는 <b>다단계 보호 계층</b> 적용</li>
        <li>HMAC-SHA256 서명 세션 쿠키로 보호되는 <b>관리자 대시보드</b> (Chart.js, 10초 주기 갱신)</li>
        <li>약 780줄 단일 <code>main.py</code>를 역할별 모듈 · 라우터로 분리, <b>Docker Compose</b> 배포 · ngrok 외부망 연동</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
    </td>
  </tr>

  <!-- ───────── RE:CASE / Asset Dashboard ───────── -->
  <tr>
    <td width="50%" valign="top">
      <h3>🕵️ <a href="https://github.com/Juntak0131/re-case">RE:CASE</a></h3>
      <b>예/아니오로 푸는 미제사건 AI 추리 게임</b><br/>
      <sub>인공지능프로젝트 · 개별 프로젝트</sub>
      <br/><br/>
      <a href="https://github.com/Juntak0131/re-case"><img src="https://github.com/Juntak0131/re-case/raw/main/docs/images/home.png" width="100%" /></a>
      <ul>
        <li>"예 · 아니오 · 관계없음"으로만 답하는 <b>AI 판정관</b>에게 질문 20개로 사건의 전말을 추리</li>
        <li>진실 원장은 서버에만 두고 <b>JSON Schema enum</b>으로 출력을 제한해 프롬프트 인젝션에 의한 정답 유출 차단</li>
        <li>의미 기반 <b>AI 채점관</b>, 질문 캐시 · IP당 요청 제한으로 비용 관리</li>
        <li>가짜 판정관을 끼운 <b>pytest</b>로 API 전체 흐름 검증</li>
      </ul>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white" />
    </td>
    <td width="50%" valign="top">
      <h3>🖥️ <a href="https://github.com/Juntak0131/asset-dashboard">Asset Dashboard</a></h3>
      <b>컴퓨팅 자산 관리 풀스택 대시보드</b><br/>
      <sub>백엔드실무프로젝트 · 2026-1 기말 프로젝트</sub>
      <br/><br/>
      <ul>
        <li><b>Genian NAC</b> 대시보드를 벤치마킹한 자산 · 시스템 리소스 관리 대시보드</li>
        <li><b>Spring Security + JWT</b> 인증, ADMIN / USER 권한 분리</li>
        <li><b>Spring AOP</b>로 등록 · 수정 · 삭제 · 할당 · 반납 작업의 감사 로그 자동 기록</li>
        <li><code>@Scheduled</code> 기반 실시간 CPU · 메모리 · 디스크 메트릭 차트</li>
        <li><b>Railway</b>(서버 · MySQL) + <b>Vercel</b>(프론트) 배포, docker-compose 로컬 실행</li>
      </ul>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <br/><br/>
      <a href="https://asset-dashboard-rho.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    </td>
  </tr>

  <!-- ───────── Cosméthique ───────── -->
  <tr>
    <td colspan="2" valign="top">
      <h3>✨ <a href="https://github.com/DMD-BackEndProject/MainProject">Cosméthique</a></h3>
      <b>AI 피부 분석 & 맞춤 화장품 추천 웹 서비스</b><br/>
      <sub>7조 팀 프로젝트 · API 연동 · 백엔드 · DB 설계 · 테스트 담당</sub>
      <ul>
        <li>얼굴 사진을 <b>Face++ API</b>로 분석해 주름 · 모공 · 홍조 · 유분 · 피부 톤 5개 지표를 자동 평가</li>
        <li>분석 결과를 DB의 제품 데이터와 매칭해 카테고리별 <b>맞춤 화장품 추천</b></li>
        <li>Servlet · DAO · DTO로 나눈 <b>Java MVC 구조</b>, 회원 · 세션 · 분석 기록 CRUD 구현</li>
      </ul>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/JSP%20%2F%20Servlet-007396?style=flat-square" />
      <img src="https://img.shields.io/badge/Apache%20Tomcat%209-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/Face%2B%2B%20API-1E90FF?style=flat-square" />
    </td>
  </tr>
</table>

<br/>

## 📊 GitHub Stats

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=Juntak0131&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakNum=FFFFFF&currStreakLabel=38BDF8&sideNums=FFFFFF&sideLabels=C9D1D9&dates=8B949E&stroke=30363D" />
</div>

<br/>

## 💼 Experience

- **동양미래대학교** 컴퓨터소프트웨어공학과 재학
- **졸업작품 UPM** (DMU-DeCode) — 서버 파트
- **인공지능프로젝트** — 생성형 AI 추리 게임 RE:CASE 개별 프로젝트
- **백엔드실무프로젝트** — Asset Dashboard 설계 · 구현 · 클라우드 배포 (2026-1)
- **Cosméthique** 7조 팀 프로젝트 — API 연동 · 백엔드 · DB 설계 · 테스트

<br/>

## 📬 Contact

<div align="center">

<a href="https://github.com/Juntak0131"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
<!-- ▼ 아래 YOUR_EMAIL 부분을 실제 이메일로 바꿔 주세요 -->
<a href="mailto:YOUR_EMAIL@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>

</div>

<!-- ===================== FOOTER ===================== -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=120&section=footer" width="100%" />
