# Pro Job Searcher - 프로이직러
- 구직정보를 크롤링하여 분석 후 시각화
### 기능 
  - 키워드 검색시, 해당하는 회사 정보 출력
  - 구직공고를 요소별로 분석해서 시각화
#### 구직정보 범위
- 신입, 0~5년차 이하
- 원하는 회사 - [리스트업](https://docs.google.com/spreadsheets/d/1QgG70dglUBQagZk_S0zch72yCZm1bgzDGaZy7n4GudM/edit?usp=sharing)

#### 가공 정보
- 기존링크 출처 명시
- 필요요소별로 가공
  - 주요업무, 자격사항, 우대사항, 연차 정보, 회사 이름, 직군명, 기술스택  
####  분석 정보 - 기술스택
  - 키워드 통계 : 어떤 키워드가 많이 쓰이는지
    - 회사에서 원하는 인재상,직무 
    - 기술스택 - 기술트렌드 보여줌.
 - 버전2. 기술스택 정보 링크 : AWS 라면  공식doc url 링크 보여주기
####  추가 제공 - 회사정보
Version.01
- 검색포털 URL(검색쿼리)정보 - 팝업출력
- 로켓펀치 소개자료(회사홈페이지 없는 스타트업의 경우) - 수동으로 DB를 통해 (링크, 회사명) 관리
Version.02
- 검색포털 API사용해서 - 검색결과, 최신 뉴스, SNS
- 잡플래닛 회사평점
- 연봉정보 - 공공데이터 - 국민연금공단 사업장 정보조회 서비스
- 회사별 도메인 분야 카테고리 등록 (it,..) 
- 로켓펀치 소개자료 등록하는 어드민 페이지 개발

### 일정
- 총 6주 (04/07 ~ 06/20)
  - 개발환경구축 (2주)
    - Docker, AWS, NginX, 무중단배포 - CI / CD (적어도 Jenkins) 
    - DBMS 설계
  - 개발 (6주)
  - 통합테스트, 문서 정리 (2주)

### 프로젝트 개발 환경
  - 크롤링 / Front-end : vue.js
  - SpringBoot, gradle, Modern Java(Java8 이후) 
  - TDD, AutomatedTest / 정적분석 : SonarQube 
  - DBMS - ORM, JPA
  - 분석: Spark
  - CI / CD : Docker, AWS,NginX, 무중단배포

### 역할분담
- 개발환경 : 공통(만나서 같이)
- 크롤링 : @ohahohah
- FrontEnd : @kimsunoh
- DB 설계 : @kimsunoh
- 기술트렌드 분석
- 인재상,직무 키워드 분석 

