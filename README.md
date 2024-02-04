# introduce
  
## 공부하여 습득한 기술
- Java 17
- Spring Framework Core
- Spring Boot
- Spring Data
- Spring Cloud (Gateway, CircuitBreaker, Stream)
- Servlet stack
  - Spring Web, JPA
- Reactive stack
  - Reactive Streams, Reactor, Netty
  - Spring Webflux, R2dbc
- MySQL, Redis, Kafka
- Layered, Clean Architecture(hexagonal)
- TDD, BDD, Mockito, JUnit5, AssertJ, Reactor test, testcontainer
- Spring REST Docs
  
## 개인 링크
- 깃헙
  - 거의 매일 커밋
- 기술 블로그
  - 포스팅 약 190 건
  
## 깃헙 리포지토리 소개 (100 커밋 이상이거나 소개드리고 싶은 repo 위주)
링크로 들어가면 더 자세한 소개가 있습니다. (가끔 부실할 수 도 있습니다..)  
소개 드린 것 외에도 다양한 프로젝트가 존재합니다.  
  
- 이론 및 Best practice study
  - leetcode
    - argorithm, sql problem
  - java
    - Java 전반, Java io, nio, aio, reactor, proactor 등
  - SpringStudyProject
    - servlet stack 기반의 Spring, JPA 전반
  - spring-webflux (공부 중)
    - reactive stack 기반의 다양한 기술들 
    - Netty, reactor, Spring Webflux, Data, Cloud 등
  - redis
    - redis 전반
  - kafka
    - kafka 전반
  - spring-guide
    - spring.io 에 소개된 간단한 가이드 따라해보기
  - CppStudy
    - mordern c++ 
  
- 실습 및 프로젝트 기반 study
  - architecture
    - layered, hexagonal architecture 공부
      - layered/splitpay : 1/N 정산 서비스, 빡센 test code, data jpa
      - hexagonal/pay : 계좌 서비스, archunit
  - hellogram (진행 중)
    - Reactive stack 으로 구현하는 모의 instagram, 각 서비스간 연동하여 MSA
      - article : clean architecture(multimodule), webflux, data mongodb reactive, cloud circuitbreaker, cloud stream with kafka, testcontainer, reactor test
      - image : webflux, data redis reactive
      - user : cloud stream with kafka
      - gateway : cloud gateway
  - test-code
    - test code 의 모든 것
      - practice/cafekiosk : 키오스크 서비스, 빡센 test code, TDD, BDD JUnit5, Mockito, AssertJ, Spring REST Docs
      - theory : todo..
  - sns-mysql
    - jdbcTemplate, JPA 로 mysql 연동 
    - RDB 와 연결된 application 에서 고민할 다양한 토픽을 다룸
    - follow, member, post 도메인을 monolithic 서버로 구현
  - first-come-first-served
    - 쿠폰 선착순 서비스 구현
      - 선착순 서비스에서 고민해야할 주제를 다룸
      - JPA, redis, kafka
  - concurrency
    - 간단한 재고 서비스를 통해 동시성 문제를 해결하는 다양한 방법을 다룸
      - JPA, redis
  - msa-ddd
    - 주문, 선물 서비스를 구현하며 msa, ddd 에 대해 다룸
