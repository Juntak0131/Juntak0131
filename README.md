<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=HAN%20JUNTAK&fontSize=70&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Backend%20Developer%20%7C%20Java%20%C2%B7%20Python%20%C2%B7%20AI&descSize=20&descAlignY=58" width="100%" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Han+Juntak;Backend+Developer+with+Spring+Boot+%26+FastAPI;Building+AI-powered+web+services" alt="Typing SVG" /></a>

<br/>

<img src="https://img.shields.io/badge/Dongyang%20Mirae%20Univ.-203A43?style=flat-square" />
<img src="https://img.shields.io/badge/Computer%20Software%20Eng.-2C5364?style=flat-square&logo=gitbook&logoColor=white" />
<img src="https://img.shields.io/badge/Backend%20Developer-203A43?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/AI%20Web%20Service-2C5364?style=flat-square&logo=fastapi&logoColor=white" />

</div>

<br/>

## 👨🏻‍💻 About Me

> **"동작하는 코드를 넘어, 믿고 쓸 수 있는 서비스를 만듭니다."**

동양미래대학교 **컴퓨터소프트웨어공학과**에서 백엔드와 AI 서비스 개발을 공부하고 있습니다.
**Spring Boot**로 JWT 인증 · 권한 분리 · AOP 감사 로그를 갖춘 자산 관리 대시보드를 만들어 직접 배포했고,
**FastAPI + OpenAI API**로 정답 유출을 구조적으로 막는 AI 추리 게임을 개발했습니다.
기능 구현에서 끝나지 않고 **보안 · 테스트 · 배포**까지 책임지는 개발을 지향합니다.

<br/>

## 🛠️ Tech Stack

<div align="center">
<table>
  <tr>
    <td align="center" width="140"><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=java,spring,python,fastapi,mysql" height="44" /></td>
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=react,vite,js,html,css" height="44" /></td>
  </tr>
  <tr>
    <td align="center"><b>AI</b></td>
    <td>
      <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" />
      <img src="https://img.shields.io/badge/Structured%20Outputs-2C5364?style=for-the-badge&logo=json&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>Infra & Tools</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=docker,vercel,git,github" height="44" />
      <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" height="44" />
    </td>
  </tr>
</table>
</div>

<br/>

## 🚀 Key Projects

<table>
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
        <li><b>Railway</b>(백엔드 · MySQL) + <b>Vercel</b>(프론트) 배포, docker-compose 로컬 실행</li>
      </ul>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <br/><br/>
      <a href="https://asset-dashboard-rho.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    </td>
  </tr>
</table>

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Juntak0131&show_icons=true&rank_icon=github&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=38BDF8&text_color=C9D1D9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Juntak0131&layout=compact&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9" />

<img src="https://streak-stats.demolab.com/?user=Juntak0131&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakNum=FFFFFF&currStreakLabel=38BDF8&sideNums=FFFFFF&sideLabels=C9D1D9&dates=8B949E&stroke=30363D" />

</div>

<br/>

## 💼 Experience

- **동양미래대학교** 컴퓨터소프트웨어공학과 재학
- **백엔드실무프로젝트** — Asset Dashboard 설계 · 개발 · 클라우드 배포 (2026-1)
- **인공지능프로젝트** — 생성형 AI 추리 게임 RE:CASE 개별 프로젝트

<br/>

## 📬 Contact

<div align="center">

<a href="https://github.com/Juntak0131"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
<!-- ▼ 아래 YOUR_EMAIL 부분을 실제 이메일로 바꿔 주세요 -->
<a href="mailto:YOUR_EMAIL@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
<!-- ▼ 이력서 페이지 주소가 열리는지 확인 후 사용하세요 (안 열리면 이 줄 삭제) -->
<a href="https://juntak0131.github.io/resume/"><img src="https://img.shields.io/badge/Resume-2C5364?style=flat-square&logo=githubpages&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Juntak0131&label=Profile%20Views&color=2C5364&style=flat-square" />

</div>

<!-- ===================== FOOTER ===================== -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=120&section=footer" width="100%" />
