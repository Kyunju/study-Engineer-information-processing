# 소프트웨어 개발 방법론

## 소프트웨어 생명주기 모델

- 소프트웨어 생명주기 모델 **개념** SDLC(Software Development Life Cycle)
  - 소프트웨어 생명주기는 시스템의 요구분석부터 유지보수까지 전 공정을 체계화 한 절차
- 소프트웨어 생명주기 모델 **프로세스**
  - 요구사항 분석 → 설계 → 구현 → 테스트 → 유지보수
  - 생명주기 모델 프로세스 별 키워드
    - 요구사항분석 : 기능 요구사항, 비기능 요구사항
    - 설계 : 시스템 구조설계, 프로그램 설계, 사용자 인터페이스(UI) 설계
    - 구현 : 인터페이스 개발, 자료구조 개발, 오류처리
    - 테스트 : 단위 테스트, 통합테스트, 시스템 테스트, 인수 테스트
    - 유지보수 : 예방, 완전, 교정, 적응, 유지보수
- 소프트웨어 생명주기 모델 **종류**
  - 폭포수 모델 Waterfall Model
    - 가장 오랜된 모델로 순차적으로 각 단계를 확실히 마무리 지은 후 다음 단계로 넘어감
    - 타당성 검토 → 계획 → 요구사항 분석 → 설계 → 구현 → 테스트 → 유지보수
  - 프로토타이핑 모델 Prototyping Model
    - 고객이 요구항 주요 기능을 프로토타입으로 구현
    - 요구사항 분석 → 프로토타입 개발 → 프로토타입 평가 → 구현 → 테스트
  - 나선형 모델 Sprial Model
    - 시스템 개발 시 **위험을 최소화**하기 위해 **점진적**으로 완벽한 시스템으로 개발하는 모델
    - 계획 및 정의 → 위험분석 → 개발 → 고객평가
  - 반복적 모델 Iteration Model
    - 병행 개발, 구축 대상을 나누어 병렬적으로 개발 후 통합하거나 반복적으로 개발
    - 개발대상 → (분석 → 설계 → 구현) x 3 병렬적으로 구성

## 소프트웨어 개발 방법론 종류

- 구조적 방법론 Structured Development
- 정보공학 방법론 Information Engineering Development
- 객체 지향 방법론
- 컴포넌트 기반 방법론
  - 컴포넌트 : 원하는 데이터베이스와 소프트웨어의 개발된 모듈 단위
- 애자일 방법론
- 제품 계열 방법론

## 애자일 방법론

- 개념
  **절차보다는 사람이 중심**이 되어 변화에 유연하고 신속하게 적응하면서 효율적으로 시스템을 개발
- 애자일 방법론의 유형
  - XP (eXtreme Programming)
    의사소통 개선과 즉각적 피드백으로 소프트웨어 품질을 높이기 위한 방법론
    - **5가지 가치**
      - 용기, 단순성, 의사소통, 피드백, 존중
      - 용기 : 피드백과 테스트를 통해 빨리 변경하고 변화할 수 있는 용기
      - 단순성 : 필요한 것만 하기
      - 의사소통 : 개발자, 관리자, 고객 원활한 소통
      - 피드백 : 의사소통에 대한 빠른 피드백
      - 존중 : 팀원 간의 상호 존중
    - 12가지 기본 원리
      다 모름 대신 몇몇 핵심만
      - **Pair Programming**
      - **CI , Continuous Integration** : 지속적인 통합, 매일 여러번 지속적으로 소프트웨어를 통합하고 빌드
      - **TDD, Test Driven Development** : 작성해야 하는 프로그램에 대한 테스트를 먼저 수행하고 테스트를 통과 할 수 있도록 코드 작성
      - **Refactoring** : 프로그램의 기능을 바꾸지 않으면서 중복제거, 단순화 등을 위해 시스템 재구성
      - **Coding Standart** : 효과적인 공동작업을 위한 표준 정리
  - 스크럼 (SCRUM)
    매일 정해진 시간 장소에 짧은 시간의 개발을 하는 팀을 위한 프로젝트 관리 중심 방법론
    - 주요프로세스
      **백로그**를 나눈 후 스크럼 팀을 구성하고 **스프린트 회의**를 거쳐 2~4주 단위의 **스프린트**를 수행한다. 수행 중 매일 **스크럼 미팅**을 수행하고 스프린트가 끝난 후에는 **스프린트 회고**를 수행
    번 다운 차트 : 남아있는 백로그 대비 시간을 그래픽적으로 표현한 차트
  - 린 LEAN
    도요타 린 시스템 품지기법을 개발 프로세스에 적용
    - 7가지 원칙
      낭비제거, 품질 내재화, 지식 창출, 늦은 확정, 빠른 인도, 사람 존중, 전체 최적화