<details>
<summary>ENG (English Version)</summary>

# Software Engineering

## 1. Development Process

### Program vs. Software Definition
- **Program**: Programming source code.
- **Software**: All outputs from the development process, including programs, data structures, test results, and user manuals.

### Software vs. Manufacturing
- **Manufacturing**: Produces products from a fixed pattern.
- **Development**: Creates new products or uses existing tech to meet goals. Software evolves with functional improvements and adaptation to new environments.

### Software Development Complexity
- The complexity of tools, processes, and team structure varies with project scale.
- **Software Engineering**: Applying engineering principles to solve problems within time and cost constraints.
- **SDLC**: The Software Development Life Cycle structures this process.

### Software Development Process
A series of activities to transform user requirements into a software system, involving procedures, methods, tools, and developers.

## 2. Software Development Models

### Build-and-Fix Model
- **Description**: Development without a formal process.
- **Characteristics**: Suitable for small, short-term projects by a single developer.
- **Disadvantages**: Lacks documentation, making maintenance difficult.

### Linear Sequential Model (Waterfall)
- **Description**: A sequential, top-down development process.
- **Procedure**: Planning → Analysis → Design → Implementation → Testing → Maintenance.
- **Advantages**: Easy to manage with clear documentation.
- **Disadvantages**: Inflexible, as requirements must be stable and are hard to verify until the end.

### Evolutionary Process Model
- **Prototype Model**: Creates an initial prototype and refines it. Ideal for unclear requirements.
- **Spiral Model**: Adds risk analysis to the prototype model, iterating through planning, risk analysis, prototyping, and evaluation.

### Phased Development Model
- **Incremental Development**: Develops core parts first, then expands scope.
- **Iterative Development**: Develops the full system, then refines subsystems.

### Unified Process Model
- **Description**: An iterative model for large, complex software.
- **Phases**: Inception → Elaboration → Construction → Transition.
- **Characteristics**: UML-based and flexible to changing requirements.

### Agile Process Model
- **Philosophy**: Rapidly responds to customer needs and changing requirements.
- **Agile Values**:
  - Individuals and interactions over processes.
  - Working software over documentation.
  - Customer collaboration over contracts.
  - Responding to change over a fixed plan.

### Scrum Framework
- **Components**: Product backlog, sprint planning, daily scrum, sprint review, sprint retrospective.
- **Roles**: Product owner, scrum master, development team.
- **Advantages**: Regular deliverables and daily coordination.
- **Disadvantages**: Requires a functional product per sprint and can have meeting overhead.

## 3. UML (Unified Modeling Language)

### UML Diagrams
Visual tools to represent system interactions, structure, and relationships.

- **Use Case Diagram**: Shows interactions between actors (users/systems) and system functions (use cases).
- **Class Diagram**: Describes system structure with classes, attributes, methods, and their relationships (association, inheritance, etc.).
- **Sequence Diagram**: Visualizes object interactions over time via message sequences.
- **Activity Diagram**: Represents workflows and behaviors during execution.
- **State Diagram**: Models the state changes of an object.
- **Component Diagram**: Shows relationships between executable modules.
- **Deployment Diagram**: Defines hardware resources and node configurations.

## 4. Planning

### Project Planning
- **Steps**: Problem definition, feasibility analysis, cost estimation, scheduling, and risk analysis.

### Feasibility Analysis
- **Economic**: Cost-benefit and market analysis.
- **Technical**: Assessment of available technology.
- **Legal**: License and intellectual property verification.

### Cost Estimation
- **Top-down**: Expert judgment, Delphi technique.
- **Bottom-up**: LOC (Lines of Code), Function Point analysis.
- **Mathematical**: COCOMO models.

### Schedule Planning
- **WBS**: Breaking the project into manageable tasks.
- **PERT/CPM & Gantt Charts**: Tools for scheduling.

### Risk Analysis
- **Process**: Identification → Analysis → Planning → Monitoring.
- **Response**: Avoidance, mitigation, transfer, acceptance.

## 5. Requirements Analysis

### Requirements Definition
- **Functional**: What the system must do.
- **Non-functional**: Quality attributes like performance, reliability, security, and usability.

### Requirements Analysis Process
1.  Data collection
2.  Requirements elicitation
3.  Documentation
4.  Verification

### Requirements Documentation
- **Requirements Specification**: A contract between users and developers that should be complete, consistent, clear, and verifiable.

## 6. Architecture and Class Design

### Design Principles
- **Divide and Conquer**: Break down complex problems.
- **Abstraction**: Focus on essentials, hide details.
- **Encapsulation**: Bundle data and methods.
- **Inheritance & Polymorphism**: Promote reuse and flexibility.

### Modularity
- **Coupling**: Interdependence between modules (aim for loose).
- **Cohesion**: Relatedness within a module (aim for strong).

### Architecture Design
- **Purpose**: Creates the software framework.
- **Styles**: Repository, client-server, layered, MVC, pipe-and-filter.

### Class Design
- **SOLID Principles**:
  - **S**ingle Responsibility Principle
  - **O**pen-Closed Principle
  - **L**iskov Substitution Principle
  - **I**nterface Segregation Principle
  - **D**ependency Inversion Principle

## 7. Design Patterns

### Categories
- **Creational**: Factory Method, Singleton, Builder.
- **Structural**: Decorator, Adapter, Facade.
- **Behavioral**: Strategy, State, Observer.

## 8. Implementation

### Standard Coding Rules
- **Purpose**: Improve readability, maintainability, and efficiency.
- **Guidelines**: Naming conventions, code structure, comments, variable declarations, and control structures.

## 9. Testing

### Testing Basics
- **Process**: Planning → Case Design → Execution → Result Analysis → Error Tracking.
- **Types**:
  - **Static Testing**: Reviews and inspections without code execution.
  - **Dynamic Testing**: Testing with code execution.
- **Levels**: Unit, integration, system, acceptance testing.

### Testing Techniques
- **Specification-Based (Black-Box)**: Equivalence partitioning, boundary value analysis.
- **Implementation-Based (White-Box)**: Statement coverage, branch coverage, path testing.

## 10. Quality

### Quality Perspectives
- **User**: Ease of use, performance.
- **Developer**: Readability, maintainability.
- **Manager**: Budget and schedule adherence.

### Quality Models & Standards
- **McCall's Model**: Defines factors like correctness, efficiency, and maintainability.
- **ISO/IEC 9126/25000 (SQuaRE)**: Standardized quality characteristics.
- **Process Models (CMMI, SPICE)**: Assess and improve development process maturity.

## 11. Project Management

### Project Characteristics
- Temporary, unique deliverables, limited resources.

### PMBOK Process Groups
1.  **Initiating**: Project definition.
2.  **Planning**: Scope, schedule, cost planning.
3.  **Executing**: Plan implementation.
4.  **Monitoring & Controlling**: Performance tracking.
5.  **Closing**: Project completion.

### Configuration Management
- **Purpose**: Systematically manage changes to software.
- **Process**: Identification → Control → Status Accounting → Audit.

### Maintenance Types
- **Corrective**: Fixing errors.
- **Adaptive**: Adapting to new environments.
- **Perfective**: Improving performance or adding features.
- **Preventive**: Preventing future errors.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

# 소프트웨어 공학

## 1. 개발 프로세스

### 프로그램 vs 소프트웨어 정의
- **프로그램**: 프로그래밍 소스 코드.
- **소프트웨어**: 개발 과정에서 생성되는 모든 산출물 (프로그램, 자료구조, 테스트 결과, 문서 등).

### 소프트웨어 vs 제조업
- **제조업**: 정해진 패턴에 따라 제품 생산.
- **개발**: 새로운 것을 만들거나 기존 기술을 활용해 목표 달성. 소프트웨어는 기능 개선, 환경 변화 적응 등 계속 진화함.

### 소프트웨어 개발의 복잡성
- 프로젝트 규모에 따라 도구, 프로세스, 팀 구성, 기간 등이 달라짐.
- **소프트웨어 공학**: 제한된 시간과 비용 안에서 과학적 지식을 사용해 문제를 해결하는 공학적 원리를 소프트웨어 개발에 적용하는 것.
- **SDLC**: 소프트웨어 개발 생명 주기 (Software Development Life Cycle).

### 소프트웨어 개발 프로세스
사용자 요구사항을 소프트웨어 시스템으로 구현하기 위한 일련의 활동으로, 절차, 방법, 도구, 개발자를 포함함.

## 2. 소프트웨어 개발 모델

### 주먹구구식 모델 (Build-and-Fix)
- **설명**: 특별한 가이드라인이나 프로세스 없이 개발.
- **특징**: 단일 개발자의 단기 프로젝트에 적합.
- **단점**: 문서화된 산출물이 없어 유지보수가 어려움.

### 선형 순차 모델 (폭포수 모델)
- **설명**: 표준화된 절차를 순차적으로 따르는 개발 방식.
- **절차**: 계획 → 분석 → 설계 → 구현 → 테스트 → 유지보수.
- **장점**: 관리가 용이하고 문서가 체계적임.
- **단점**: 요구사항이 안정적이어야 하고, 최종 단계까지 요구사항 검증이 어려움.

### 진화적 프로세스 모델
- **프로토타입 모델**: 초기 시제품을 만들고 수정 과정을 반복. 불명확한 요구사항에 적합.
- **나선형 모델**: 프로토타입 모델에 위험 분석을 추가. 계획, 위험 분석, 프로토타입 제작, 평가를 반복.

### 단계적 개발 모델
- **증분 개발**: 중요한 부분부터 개발 후 점차 범위 확장.
- **반복 개발**: 전체 시스템을 먼저 개발 후 각 하위 시스템을 개선.

### 통합 프로세스 모델
- **설명**: 대규모 복합 소프트웨어를 위한 반복적 개발 모델.
- **단계**: 도입 → 상세화 → 구축 → 전환.
- **특징**: UML 기반, 요구사항 변경에 유연하게 대응.

### 애자일 프로세스 모델
- **철학**: 고객 요구에 신속히 대응하고 변화에 적응.
- **애자일 가치**:
  - 프로세스보다 개인과 상호작용.
  - 문서보다 동작하는 소프트웨어.
  - 계약보다 고객과의 협력.
  - 계획보다 변화에 대한 대응.

### 스크럼 프레임워크
- **구성요소**: 제품 백로그, 스프린트 계획, 데일리 스크럼, 스프린트 리뷰, 회고.
- **역할**: 제품 책임자, 스크럼 마스터, 개발팀.
- **장점**: 주기적인 결과물, 매일의 조율.
- **단점**: 스프린트마다 동작하는 제품이 필요하며, 회의 부담이 있을 수 있음.

## 3. UML (통합 모델링 언어)

### UML 다이어그램
시스템 상호작용, 구조, 관계를 시각적으로 표현하는 도구.

- **유스케이스 다이어그램**: 액터(사용자/시스템)와 시스템 기능(유스케이스) 간 상호작용을 표현.
- **클래스 다이어그램**: 클래스, 속성, 메서드 및 그들 간의 관계(연관, 상속 등)로 시스템 구조를 설명.
- **시퀀스 다이어그램**: 시간 흐름에 따른 객체 간 메시지 순서로 상호작용을 시각화.
- **활동 다이어그램**: 실행 중 발생하는 동작과 활동의 흐름을 표현.
- **상태 다이어그램**: 객체의 상태 변화를 모델링.
- **컴포넌트 다이어그램**: 실행 가능한 모듈 간의 관계를 표시.
- **배포 다이어그램**: 하드웨어 자원과 노드 구성을 정의.

## 4. 계획

### 프로젝트 계획
- **과정**: 문제 정의, 타당성 분석, 비용 산정, 일정 계획, 위험 분석.

### 타당성 분석
- **경제적**: 비용-편익 및 시장성 분석.
- **기술적**: 사용 가능한 기술 평가.
- **법률적**: 라이선스 및 지적 재산권 검증.

### 비용 산정
- **하향식**: 전문가 판단, 델파이 기법.
- **상향식**: LOC(코드 라인 수), 기능 점수 분석.
- **수학적**: COCOMO 모델.

### 일정 계획
- **WBS**: 프로젝트를 관리 가능한 작업으로 분할.
- **PERT/CPM 및 간트 차트**: 일정 관리를 위한 도구.

### 위험 분석
- **프로세스**: 식별 → 분석 → 계획 → 감시.
- **대응**: 회피, 완화, 전가, 수용.

## 5. 요구사항 분석

### 요구사항 정의
- **기능적 요구사항**: 시스템이 반드시 수행해야 할 기능.
- **비기능적 요구사항**: 성능, 신뢰성, 보안, 사용성 등 품질 속성.

### 요구사항 분석 프로세스
1.  자료 수집
2.  요구사항 도출
3.  문서화
4.  검증

### 요구사항 문서화
- **요구사항 명세서**: 사용자와 개발자 간의 계약. 완전성, 일관성, 명확성, 검증 가능성 등을 갖춰야 함.

## 6. 아키텍처 및 클래스 설계

### 설계 원칙
- **분할과 정복**: 복잡한 문제를 작은 부분으로 나눔.
- **추상화**: 핵심 특징에 집중하고 세부 사항은 숨김.
- **캡슐화**: 데이터와 메서드를 함께 묶음.
- **상속 및 다형성**: 재사용성과 유연성 증진.

### 모듈화
- **결합도**: 모듈 간 상호 의존도 (느슨해야 좋음).
- **응집도**: 모듈 내 요소들의 관련성 (강해야 좋음).

### 아키텍처 설계
- **목적**: 소프트웨어의 기본 구조를 만듦.
- **스타일**: 저장소, 클라이언트-서버, 계층, MVC, 파이프-필터.

### 클래스 설계
- **SOLID 원칙**:
  - **S**ingle Responsibility Principle (단일 책임 원칙)
  - **O**pen-Closed Principle (개방-폐쇄 원칙)
  - **L**iskov Substitution Principle (리스코프 치환 원칙)
  - **I**nterface Segregation Principle (인터페이스 분리 원칙)
  - **D**ependency Inversion Principle (의존성 역전 원칙)

## 7. 디자인 패턴

### 패턴 분류
- **생성 패턴**: 팩토리 메서드, 싱글턴, 빌더.
- **구조 패턴**: 데코레이터, 어댑터, 파사드.
- **행위 패턴**: 스트래티지, 스테이트, 옵저버.

## 8. 구현

### 표준 코딩 규칙
- **목적**: 가독성, 유지보수성, 개발 효율성 향상.
- **지침**: 네이밍 규칙, 코드 구조, 주석, 변수 선언, 제어 구조 등.

## 9. 테스팅

### 테스팅 기초
- **프로세스**: 계획 → 케이스 설계 → 실행 → 결과 분석 → 오류 추적.
- **종류**:
  - **정적 테스팅**: 코드 실행 없이 리뷰나 인스펙션 수행.
  - **동적 테스팅**: 코드 실행을 통해 테스트.
- **단계**: 단위, 통합, 시스템, 인수 테스트.

### 테스팅 기법
- **명세 기반(블랙박스)**: 동등 분할, 경계값 분석.
- **구조 기반(화이트박스)**: 구문, 분기, 경로 커버리지.

## 10. 품질

### 품질 관점
- **사용자**: 사용 편의성, 성능.
- **개발자**: 가독성, 유지보수성.
- **관리자**: 예산 및 일정 준수.

### 품질 모델 및 표준
- **맥콜 모델**: 정확성, 효율성, 유지보수성 등 품질 요인 정의.
- **ISO/IEC 9126/25000 (SQuaRE)**: 표준화된 품질 특성.
- **프로세스 모델 (CMMI, SPICE)**: 개발 프로세스 성숙도 평가 및 개선.

## 11. 프로젝트 관리

### 프로젝트 특성
- 한시성, 고유한 결과물, 제한된 자원.

### PMBOK 프로세스 그룹
1.  **착수**: 프로젝트 정의.
2.  **계획**: 범위, 일정, 비용 계획.
3.  **실행**: 계획 이행.
4.  **감시 및 통제**: 성과 추적.
5.  **종료**: 프로젝트 완료.

### 형상 관리
- **목적**: 소프트웨어 변경사항을 체계적으로 관리.
- **프로세스**: 식별 → 통제 → 상태 보고 → 감사.

### 유지보수 유형
- **수정 유지보수**: 오류 수정.
- **적응 유지보수**: 새로운 환경에 적응.
- **완전화 유지보수**: 성능 개선 또는 기능 추가.
- **예방 유지보수**: 미래의 오류 예방.

</details>

