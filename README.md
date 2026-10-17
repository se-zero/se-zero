<h1 align="center">정세영 · Backend Developer</h1>

<p align="center">
  속도를 높일 때 정확성까지 함께 검증하는 백엔드 개발자
</p>

## About Me

- 처리 속도를 올릴 때 **순서 · 누락 · 정합성**이 지켜지는지를 수치로 함께 확인합니다.
- 졸업 작품 [whycode](https://why-code.com)에서 수집 파이프라인을 빠르게 만들면서 결과가 기존과 같은지 검증했고, 다뤄 보지 못한 몰림 상황은 따로 실험을 만들어 방식별 한계를 측정했습니다.
- 서울과학기술대학교 컴퓨터공학과 (2021.03 ~ 2027.02 졸업 예정)

## Tech Stack

| | |
|---|---|
| **Language** | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) |
| **Infra · Ops** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white) |

## Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://why-code.com"><img src="assets/why-code.png" alt="why-code.com 메인 화면"></a>
      <h3><a href="https://why-code.com">whycode</a></h3>
      <p>분산된 협업 데이터를 수집해 데이터 간 의미적 관계를 명시하는 지식 그래프를 구축하고, GraphRAG 기반 AI 추론 엔진으로 사용자의 자연어 질의에 코드 변경의 맥락과 의사결정 배경을 자동으로 설명하는 서비스</p>
      <p><sub>2026.03 ~ 진행 중 · 2인 팀 (캡스톤디자인)<br><b>수집 파이프라인 담당</b></sub></p>
      <ul>
        <li>GitHub 수집 약 10분 → <b>2분 42초</b></li>
        <li>초기 수집 약 54분 → <b>30분</b> (커밋당 7.3초 → 3.5초)</li>
        <li>PR 리뷰 봇 도입, 머지 전 고칠 문제 <b>33건</b> 지적</li>
      </ul>
      <p><sub><code>Spring Boot</code> <code>FastAPI</code> <code>RabbitMQ</code> <code>Neo4j</code> <code>PostgreSQL</code></sub></p>
      <p><a href="https://why-code.com">Site</a> · <a href="https://github.com/se-zero/history-tracker">Repo</a></p>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/se-zero/coupon-contention-lab">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="assets/coupon-dark.png">
          <img src="assets/coupon-light.png" alt="재고 차감 전략 5개의 처리량과 P99 비교 그래프">
        </picture>
      </a>
      <h3><a href="https://github.com/se-zero/coupon-contention-lab">coupon-contention-lab</a></h3>
      <p>선착순 쿠폰 발급의 재고 차감 전략 5개와 캐시 전략 5개를 같은 조건에서 3회씩 측정해 설계를 정한 실험 프로젝트</p>
      <p><sub>2026.09 · 개인 프로젝트</sub></p>
      <ul>
        <li>서버 3대에서 JVM 로컬 락이 <b>50,000건 초과 발급</b>하는 것을 재현</li>
        <li>Redis 원자 연산만 P99 500ms 기준 통과, 처리량 <b>16배</b></li>
        <li>캐시 스탬피드를 실제로 줄인 건 뮤텍스뿐임을 확인</li>
      </ul>
      <p><sub><code>Spring Boot</code> <code>Redis</code> <code>PostgreSQL</code> <code>k6</code> <code>Grafana</code></sub></p>
      <p><a href="https://github.com/se-zero/coupon-contention-lab">Repo</a> · <a href="https://github.com/se-zero/coupon-contention-lab/blob/main/ARCHITECTURE.md">설계 문서</a></p>
    </td>
    <td width="33%" valign="top">
      <a href="https://teamcrazyperformance.com"><img src="assets/tcp-website.png" alt="teamcrazyperformance.com 메인 화면"></a>
      <h3><a href="https://github.com/TeamCrazyPerformance/TCP_Website_2025">TCP_Website_2025</a></h3>
      <p>서울과학기술대학교 컴퓨터공학과 학술동아리 TCP의 공식 웹사이트</p>
      <p><sub>2025.06 ~ 2026.02 · 5인 팀<br><b>백엔드 담당</b></sub></p>
      <ul>
        <li>회원·팀·공지사항·관리자 API 개발</li>
        <li>API 응답의 개인정보 노출 수정</li>
      </ul>
      <p><sub><code>NestJS</code> <code>TypeORM</code> <code>PostgreSQL</code> <code>Docker</code> <code>ELK</code></sub></p>
      <p><a href="https://teamcrazyperformance.com">Site</a> · <a href="https://github.com/TeamCrazyPerformance/TCP_Website_2025">Repo</a> · <a href="https://github.com/TeamCrazyPerformance/TCP_Website_2025/pulls?q=is%3Apr+author%3Ase-zero">내 PR</a></p>
    </td>
  </tr>
</table>

## Contact

📧 jso8831@naver.com
