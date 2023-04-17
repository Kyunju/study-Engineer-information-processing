# 소프트웨어 아키텍처

## 소프트웨어 아키텍처 4+1 뷰

- 개념
  고객의 요구사항을 정리해 놓은 시나리오를 4개의 관점에서 바라보는 소프트웨어적인 접근 방법
- 구성요소
  - 4 : 논리뷰, 구현뷰, 프로세스 뷰, 배포 뷰
  - 1 : 유스케이스 뷰
- 각 뷰의 개념
  - 유스케이스 뷰 : 시스템이 액터에게 제공해야 하는 기능으로서 요구사항, 사용자 입장에서 바라본 시스템의 기능
  - 논리뷰 : 시스템의 기능적인 요구사항이 어떻게 제공되는지 설명
  - 프로세스 뷰 : 시스템의 비기능적인 속성, 자원 효율 사용, 병행, 실행, 비동기 등
  - 구현 뷰 : 개발 환경 안에서 정적인 소프트웨어 모듈의 구성을 보여주는 뷰
  - 배포 뷰 : 컴포넌트가 물리적인 아키텍처에 어떻게 배치 되는가 매핑해서 보여주는 뷰
    <br>

## 소프트웨어 아키텍처 패턴

- 패턴 유형

  - 계층화 패턴 (Layered Pattern)
    시스템을 계층으로 구분하여 구성하는 패턴
  - 클라이언트 서버 패턴 ( Client-ServerPattern)
    하나의 서버와 다수의 클라이언트로 구성 클라이언트가 요청하면 서버가 제공
  - 파이프-필터 패턴 ( Pipe - Fileter Pattern)
    데이터 스트림을 생성하고 처리하는 시스템에서 사용 가능한 패턴, 서브 시스템을 거치면서 데이터가 변화됨
  - 브로커 패턴 ( Broker Pattern)
    분리된 컴포넌트들로 이루어진 분산 시스템에서 사용됨, 브로커 컴포넌트가 컴포넌트 간의 통신을 조정하는 역할 수행
  - 모델,뷰,컨트롤러 패턴 (MVC, Model View Controller Pattern)
    - 모델 : 핵심 기능과 데이터 보관
    - 뷰 : 사용자에게 정보 표시
    - 컨트롤러 : 사용자로부터 요청을 입력받아 처리

    <br>
    <br>

  # 디자인 패턴

  소프트웨어 공학의 소프트웨어 설계에서 공통으로 발생하는 문제에 대해 자주 쓰이는 설계 방법을 정리한 패턴

  ## 디자인 패턴 종류

  ### 생성 패턴

  - Builder
  - Prototype
  - Factory Method
  - Abstract Factory
  - Singleton

  ### 구조 패턴

  - Bridge
  - Decorator
  - Facade
  - Flyweight
  - Proxy
  - Compostie
  - Adapter

  ### 행위 패턴

  - Mediator
  - InterPreter
  - Iterator
  - Template Method
  - Observer
  - State
  - Visitor
  - Command
  - Strategy
  - Memento
  - Chain of Responsibility
