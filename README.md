# 스프링 JPA 스터디 (20240301 ~ 20240531)


## 참여 인원
| [이창의](https://github.com/changuii) | [이종현](https://github.com/2-jjong) | [김지후](https://github.com/jihukimme) | [오민규](https://github.com/kormk) | [한동근](https://github.com/l0o0lv) |
| --- | --- | --- | --- | --- |
|  <img src="https://avatars.githubusercontent.com/u/122252160?v=4" alt="spring" width="100" height="100"/>   |  <img src="https://avatars.githubusercontent.com/u/127838675?v=4" alt="spring" width="100" height="100"/>   |  <img src="https://avatars.githubusercontent.com/u/127816292?v=4" alt="spring" width="100" height="100"/>    | <img src="https://avatars.githubusercontent.com/u/63334787?v=4" alt="spring" width="100" height="100"/>   |  <img src="https://avatars.githubusercontent.com/u/128709695?v=4" alt="spring" width="100" height="100"/>  |

## 규칙
- 매주 두 챕터씩 공부합니다.
- 매주 공부한 내용에 대해 발표를 준비하고 발표자를 당일 선정하여 발표를 진행합니다.
- 학습한 챕터는 MarkDown 으로 정리해서 깃허브 각자의 branch 에 파일을 올립니다.
- 토론 후 정리한 MD 파일의 PR을 생성한후 Main에 병합합니다.
- 매주 금요일 20시~22시

## 파일명
마크다운 파일은 [O주차-0장]OOO.md (OOO은 이름)

## 불참
- 벌금 만원 (추후 배분), 릴스 촬영
  

## 일정

발표자 : ✅  
불참 : 😵  

| 주차             | 이창의 | 이종현 | 김지후 | 오민규 | 한동근 |
| ---------------- | ------ | ------ | ------ | ------ | ------ |
| 예시 |   ✅     |   ✅     |     ✅   |   ✅     |   ✅     |
| 1주차 (3월 2일)  |      |      |    |  ✅    |      |
| 2주차 (3월 8일)  |        |    ✅    |        |        |        |
| 3주차 (3월 15일)  |   ✅  5장   |        |   ✅ 4장   |        |        |
| 4주차 (3월 22일)  |    ✅  7장    |        |        |        |   ✅  6장     |
| 5주차 (3월 30일)  |  ✅  9장      |        |        |   ✅  8장     |        |
| 6주차 (4월 7일)  |        |   ✅ 10장 페치조인 전     |        |        | ✅  10장 페치조인 후       |
| 7주차 (4월 12일)  |        |        |        |  ✅ 10장 Criteria, QueryDSL    |      ✅ 10장 네이티브SQL, 객체지향 쿼리 고급  |
| 8주차 (4월 19일)  |        |        |        |        |        |
| 9주차 (4월 26일)  |        |        |        |        |        |
| 10주차 (5월 3일) |        |        |        |        |        |
| 11주차 (5월 10일) |        |        |        |        |        |
| 12주차 (5월 17일) |        |        |        |        |        |
| 13주차 (5월 24일) |        |        |        |        |        |
| 14주차 (5월 31일) |        |        |        |        |        |

## 주차별 정리

### [1주차 - JPA 소개와 시작](https://github.com/changuii/Spring-Data-JPA/tree/main/%ED%95%99%EC%8A%B5%EC%9E%90%EB%A3%8C/1%EC%A3%BC%EC%B0%A8)

> JPA 소개와 시작
- JPA가 왜 탄생했고 JPA를 사용하기 전에는 어떤 문제점이 있었는지 알아본다.
- JPA로 바뀌면서 어떤 부분이 추상화되고 어떤 부분이 개발자가 편리하게 개발할 수 있는지 알아본다.
  
### [2주차 - JPA 영속성 관리](https://github.com/changuii/Spring-Data-JPA/tree/main/%ED%95%99%EC%8A%B5%EC%9E%90%EB%A3%8C/2%EC%A3%BC%EC%B0%A8)

> JPA 영속성 관리
- JPA의 영속성 관리를 알아본다.
- JPA에서 어떻게 저장, 조회, 수정, 삭제가 이루어지는지 알아본다.
- 1차 캐시, 동일성 보장, 쓰기 지연, 변경 감지 등의 기능들이 어떻게 제공되는지 알아본다.

### [3주차 - 엔티티 매핑, 연관관계 매핑](https://github.com/changuii/Spring-Data-JPA/tree/main/%ED%95%99%EC%8A%B5%EC%9E%90%EB%A3%8C/3%EC%A3%BC%EC%B0%A8)

> `엔티티 매핑`
- JPA의 다양한 매핑 어노테이션들을 알아본다.
- 객체와 테이블 매핑, 기본 키 매핑, 필드와 컬럼 매핑을 알아본다.
- 기본 키 생성 전략, DDL 자동 생성, 이름 매핑 전략에 대하여 알아본다.
> `연관관계 매핑`
- JPA의 연관관계 매핑 어노테이션들을 알아본다.
- 객체의 연관관계와 데이터베이스의 연관관계의 차이점과 매핑을 알아본다.
- 양방향, 단방향 연관관계, mappedBy 연관관계 주인에 대해서 알아본다.

### [4주차 - 다양한 연관관계 매핑과 고급 매핑](https://github.com/changuii/Spring-Data-JPA/tree/main/%ED%95%99%EC%8A%B5%EC%9E%90%EB%A3%8C/4%EC%A3%BC%EC%B0%A8)

> `다양한 연관관계 매핑` 
- 다대다, 다대일, 일대다, 일대일 등 다양한 연관관계 매핑에 대해서 알아본다.
- 연관관계를 매핑할 때 고려해야할 3가지에 대해서 알아본다. 

> `고급 매핑`
- 데이터베이스의 슈퍼 클래스, 서브 클래스에 객체의 상속 개념을 통해 매핑하는 것을 알아본다.
- 매핑 정보만 상속하는 @MappedSuperclass에 대해 알아본다.
- 데이터베이스 설계의 식별관계와 비식별관계 그리고 복합 키 매핑에 대해서 알아본다.
- 데이터베이스의 연관관계를 외래 키뿐만 아니라 연결 테이블을 사용한 방법에 대해 알아본다.
- 엔티티 하나에 여러 테이블을 매핑하는 방법에 대해서 알아본다.

### [5주차 - 프록시와 연관관계 관리, 값 타입](https://github.com/changuii/Spring-Data-JPA/tree/main/%ED%95%99%EC%8A%B5%EC%9E%90%EB%A3%8C/5%EC%A3%BC%EC%B0%A8)

> `프록시와 연관관계 관리`
- JPA에서 제공하는 프록시에 대해 알아본다.
- 데이터베이스에서 필요할 때 조회하는 지연로딩과 즉시 조회하는 즉시로딩에 대해 알아본다.
- 영속성 전이들에 대해 알아본다.
- 고아 객체 제거 기능에 대해 알아본다.

> `값 타입`
- ORM에서 분류하는 값 타입이 무엇인지 알아본다.
- 여러 기본 값을 묶어서 객체지향적으로 정의할 수 있는 임베디드 타입에 대해 알아본다.
- 컬렉션 값 타입에 대해 알아본다.
- 불변 객체란 무엇인지 알아본다.

### [6주차 - 객체지향 쿼리 언어 (JPQL)](https://github.com/changuii/Spring-Data-JPA/tree/main/%ED%95%99%EC%8A%B5%EC%9E%90%EB%A3%8C/6%EC%A3%BC%EC%B0%A8)
- Criteria, QueryDSL, JPQL에 대해 알아본다.
- 페이징, 페치 조인, 파리미터 바인딩, 집합과 정렬, 서브쿼리, 다형성 조인, NamedQuery에 대해 알아본다.

### [7주차 - 객체지향 쿼리 언어 (Criteria, QueryDSL, 고급 객체지향 쿼리)](https://github.com/changuii/Spring-Data-JPA/tree/main/%ED%95%99%EC%8A%B5%EC%9E%90%EB%A3%8C/7%EC%A3%BC%EC%B0%A8)
- Criteria, QueryDSL, 네이티브 SQL에 대해서 자세히 알아본다.
- 플러시 모드를 통한 최적화와 JPQL의 동작을 알아본다.
- 벌크 연산에 대해서 알아본다.