# ✨Baek Min Jeong✨
- **📫Email** : chungchung3701@gmail.com
- **📫Blog** : https://yangheeb.tistory.com
  
![](/github-metrics.svg)

## Summary
> 안녕하세요! Java와 Spring Boot를 활용해 물류 및 이커머스 도메인에 특화된 백엔드 시스템을 개발하는 개발자입니다. 

> 물류 프로덕트에 기여할 수 있는 실시간 주문 처리, 재고 관리, 배송 최적화 시스템을 구축한 경험이 있습니다. 

> ERP의 주문, 재고, 운송 관리 모듈에서 영감을 받아 확장 가능하고 효율적인 솔루션을 설계합니다.👩🏻‍💻

## Skills
### Tech: 한 번 이상 다루어 본 기술들
- **Language** : <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=Java&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white">
- **DBMS** : <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=Oracle&logoColor=white"/> <img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-00684A?style=flat-square&logo=MongoDB&logoColor=white"/> <img src="https://img.shields.io/badge/Neo4j-4479A1?style=flat-square&logo=Neo4j&logoColor=white"/></a>
- **Framework** :<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white" /> <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/>
- **Tools** : <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=Slack&logoColor=white"/> <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=flat-square&logo=intellij-idea&logoColor=white" /> <img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=flat-square&logo=visual%20studio%20code&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/UIPath-FA4616?style=flat-square&logo=UIPATH&logoColor=white"/></a>

+ Oracle, MySQL, MongoDB, Neo4j를 사용하여 데이터베이스 구축하고 질의 분석 경험 
+ UIPath를 사용하여 RPA 프로세스 개발 경험 

### 앞으로 공부할 것들 (계획 중인 프로젝트)
- ### 전국 날씨 정보 API 백엔드 서버
  : 기상청 오픈API를 활용하여 전국 날씨 정보를 수집하고, 이를 MySQL에 저장 후 REST API로 제공하는 백엔드 서버 구축
- **주요기술**: Java, Spring Boot, MySQL, JPA, AWS EC2
- **주요기능**:

  - 외부 오픈API에서 JSON 데이터 받아오기
  - 날씨 데이터를 정제하여 DB에 저장
  - 최신 날씨 정보를 조회하는 REST API 제공
  - AWS EC2 서버에 배포 및 운영

## Projects
- 웹 페이지 제작 ( 2023.11 ~ 12 )
- [ Past-Forward BE ] [회고 보드 웹 서비스 ](https://github.com/donga-it-club/past-foward-backend) ( 2024.03 ~ 07 )
  - https://pastforward.link
  - 팀원 초대 API 설계 및 구현
  - 공지사항 게시판 API 설계 및 구현
- [ RPA ] 시간표 알림 자동화 프로세스 ( 2024.12 )
- 실시간 주문 처리 및 물류 추적 시스템
  - 개요: 고객 주문 관리와 물류 상태(주문 접수, 포장, 배송 중, 배송 완료)를 실시간 추적하는 백엔드 시스템. ERP 주문 관리 및 물류 관리 모듈 참고.
  - 기술: Java 17, Spring Boot, PostgreSQL, Redis, RabbitMQ, Swagger
  - 구현:
RESTful API: 주문 생성/상태 업데이트/추적 (POST /api/orders, PATCH /api/orders/{id}/status, GET /api/orders/{id}/track).
Redis 캐싱으로 주문 상태 조회 속도 40% 향상.
RabbitMQ로 비동기 알림 구현.
@Transactional로 트랜잭션 무결성 보장.
  - 성과:
Swagger API 문서화.
JMeter로 500명 동시 요청 처리 (평균 200ms 응답).
JPA 기반 데이터베이스 최적화.


- 창고 재고 관리 시스템
  - 개요: 창고 재고를 실시간 관리하고 입출고를 최적화하는 백엔드 시스템. ERP 재고 관리 및 창고 관리(WMS) 모듈 반영.
  - 기술: Java 17, Spring Boot, MySQL, Spring Cache, Docker, Flyway
  - 구현:
    RESTful API: 재고 등록/조회/입출고 (POST /api/inventory, GET /api/inventory?category=food, POST /api/inventory/{id}/transaction).
@Transactional(SERIALIZABLE)로 동시성 제어.
Spring Cache로 조회 성능 30% 향상.
Slack Webhook으로 재고 부족 알림.
  - 성과:
Flyway로 데이터베이스 마이그레이션 자동화.
300개 동시 트랜잭션 처리 테스트 성공.
Docker로 배포 환경 구축.

- 배송 경로 최적화 시스템
  - 개요: 배송 경로를 최적화하고 물류 상태를 모니터링하는 백엔드 시스템. ERP 운송 관리 모듈 참고.
  - 기술: Java 17, Spring Boot, PostgreSQL, Spring for GraphQL, OR-Tools, Spring Async
  - 구현:
OR-Tools로 경로 최적화 API (POST /api/routes/optimize), 배송 시간 15% 단축.
GraphQL API로 상태 조회 (예: { route(id: "123") { status, eta } }).
Spring Async로 지연 알림 비동기 처리.
PostgreSQL 인덱싱으로 조회 최적화.
  - 성과:
GraphQL 스키마 설계 및 샘플 쿼리 제공.
Maven과 GitHub Actions으로 CI/CD 구현.
OR-Tools로 비용 20% 절감 (시뮬레이션).
  

## Education
**🌱 I'm currently learning MIS, Dong-A University** ( 2022.03 ~ now )
> - 시스템분석및설계
> - MIS
> - 데이터베이스시스템(I)
> - 데이터베이스시스템(II)
> - 웹프로그래밍
> - 프로그래밍기초
> - 프로그래밍언어
> - 네트워크의이해
> - 경영혁신과RPA
> - R기반통계분석
> - 빅데이터분석
> - 텍스트분석

**🌱 Study**
- 동아대 IT 취업 동아리 SQL 스터디 ( 2024.01 ~ 03 )
- 동아대 IT 취업 동아리 Spring 스터디 ( 2024.02 ~ 03 )

## Certificate
- SQLD ( 2024.04 )
<!--
**yangheeb/yangheeb** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

