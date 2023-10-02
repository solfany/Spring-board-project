# board project v.1.1
---
### 데모 페이지 
https://project-board-solfany-097b91237c20.herokuapp.com/

<br>
<br>

## 개발 환경
![4](https://github.com/solfany/Spring-board-project/assets/123814718/b7f6bf86-d57c-414a-a557-d1695745ef0d)

각종 개발 전략과 도메인 설계, 실무 디자인 패턴, 비즈니스 로직의 구현을 경험


## 사용자 화면 - 메인
![image](https://github.com/solfany/Spring-board-project/assets/123814718/bf0e18dc-546c-40b8-92d0-ff1a4d5a4dce)

## 사용자 화면 -해시태그 게시판 
![image](https://github.com/solfany/Spring-board-project/assets/123814718/f44c9b87-ba38-4d39-a81e-9f0c1247e5c1)


## 사용자 화면 - 카카오 로그인 
![image](https://github.com/solfany/Spring-board-project/assets/123814718/ebcb0432-8c2c-4c13-af4b-ba9f33d1ce91)
<br>
![image](https://github.com/solfany/Spring-board-project/assets/123814718/65480db7-3a31-41b4-8be7-49e026523484)

## 사용자 화면 - 게시글 작성 
![image](https://github.com/solfany/Spring-board-project/assets/123814718/79a0b821-8133-49cc-8338-0b7c12e308d9)

## 사용자 화면 - 게시글 확인 
![image](https://github.com/solfany/Spring-board-project/assets/123814718/c43f067b-b5c6-45b3-a8f7-66f5cf5d4828)


## 1. 게시판 서비스 프로젝트 목표

1. 명확한 기능 요구 사항을 만든다.
2. 요구 사항을 구현하는데 도움이 되는 각종 문서 작업을 한다. 
3. 자바 + 스프링부트로 프로젝트 요구 사항을 실제로 구현 
4. 기획과 문서 작성부터 개발 형상 관리, 테스트, 배포까지 개발 프로세스를 실무와 가깝게 경험한다. 
5. 개발 목적 명확히 하기
>
> 

### 1-1. 프로젝트 명확한 요구 사항

> 완벽하고 기본적인 게시판 기능 구현 
현업에서 사용하는 실제 기능들을 활용할 것 (유료버전이라도)
> 

## 2. 프로젝트 문서화
![5](https://github.com/solfany/Spring-board-project/assets/123814718/125eeca1-01d3-4be5-b866-09457f47e0c1)


### 2-1. 실무 프로젝트 처럼 필요한 서류 조사 및 작성
•  도메인 ERD 설계, 유즈케이스
•  API 디자인 
•  커밋 메세지, 프로젝트 관리 및 협업 환경
> 

## 3. 자바 + 스프링부트로 프로젝트 요구 사항

> 코드의 가독성에 집중하고,  이슈 해결 과정 명시하기
협업이라는 가정하고, 가상의 팀원이 봐도 이해하기 쉬운 구조와 깔끔한 코드, 버전 관리
> 

## 4. 개발 형상 관리, 테스트, 배포

> 자바 + 스프링의 프로젝트의 경우 배포 및 테스트는 어떻게 진행되는지
사용자 베타 테스트 후 피드백 수렴 및 문서로 기록 남겨두기
> 

## 5. 개발 목적

> 모든 과정에서의 학습을 목표로 오랜시간이 걸려도 배움의 자세로..
가능한 최신 버전의 기술을 접해보자 
최신 동향 파악 

테스트와 배포 - 고객에게 제품을 보여주고 성과를 확인하는 순간
> 
> 
> 테스트
> • 개발 요구사항이 빠짐 없이 모두 구현되었는가 (일이 끝났는가)
> • 구현된 요구사항이 오류 없이 동작하는가 (일이 잘 끝났는가)
> 
> 배포
> • 깃헙 릴리즈 작성
> • 클라우드 서버에 배포 (헤로쿠)
> 
> 이 게시판 만들기 프로젝트에서 해볼 테스트와 배포는...
> 
> 테스트
> • JUnit 5.8.2
> • 각종 테스트 라이브러리 (Mockito, AssertJ 등)
> • 스프링 부트 슬라이스 테스트 테크닉• 깃헙: 테스트/빌드 자동화
> 
> 배포
> • 클라우드 서버에 배포 (Heroku)
> 
> 최근 보안 이슈로 일부 자동화 기능을 이용하지 못할 수 있음
> 
> Heroku 를 사용하지 못할 경우, 로컬에서 실행
> • 깃헙: Heroku 배포 자동화
> 

## 6. 필요 세부 기술 목록 추출 방법

- 미리 사용 기술을 설계한 후 처음부터 프로젝트 도입
- 기능 하나를 추가 할 때마다 필요한 기술을 추가해 나가는 방법
> 

## 7. 예상하는 세부 기능들

> • 게시판, 댓글 도메인의 설계
• 도메인 데이터를 DB 에 저장
• JSON API 로 데이터 제공
• 사용자에게 웹 화면으로 서비스 제공 + 디자인 요소
• 적절한 입출력 데이터의 검증
• 인증 기능
• 생산성에 도움이 되는 도구들 선택
> 

## 8. 세부 기능으로부터 선택을 예상하는 기술들

> • Java + Spring Boot 기반에서 선택
• 웹 서비스 제공 -> Spring Web
• 도메인의 설계와 DB 저장 -> Spring Data JPA, H2 Database, MySQL Driver
• JSON API 로 데이터 제공 -> Rest Repositories, Rest Repositories HAL Explorer
• 웹 화면: 프로젝트 목표에 맞춰 서버 사이드 렌더링으로 접근 -> 템플릿 엔진 -> Thymeleaf 
• 디자인 요소 -> Bootstrap 5.2
• 적절한 입출력 데이터의 검증 -> Validation
• 인증 기능 -> Spring Security
• 생산성 -> Lombok, Spring Boot DevTools, Spring Boot Actuator



## 기능소개 

![6](https://github.com/solfany/Spring-board-project/assets/123814718/33dd6977-3fd7-4fc6-ac84-a0fbd1ef58d1)



## 이슈사항 

![7](https://github.com/solfany/Spring-board-project/assets/123814718/50bc297c-4f73-4b52-a1f7-b47a5d6fc380)


![8](https://github.com/solfany/Spring-board-project/assets/123814718/c7c19033-03a9-44a8-9679-086b60d6b222)


![9](https://github.com/solfany/Spring-board-project/assets/123814718/23d19570-03af-4631-a8c1-a3c69f3c1b3a)


## 회고 

![10](https://github.com/solfany/Spring-board-project/assets/123814718/ef41c614-ab10-4d00-b250-33f2b8f5441b)




