# Software Engineering


## 1. Development Process

### Program vs Software Definition
- **Program**: Programming source code
- **Software**: All outputs generated during development process (programs, data structures, database structures, test results, documents, user manuals)

### Software vs Manufacturing
- **Manufacturing**: Producing products according to fixed patterns
- **Development**: Creating new things or utilizing existing technology to achieve goals
- **Software characteristics**: Functional improvements, new features, adaptation to environmental changes (OS, etc.)

### Software Development Complexity
- **Small vs Large Scale**: Tools, process complexity, team composition, project duration
- **Software engineering**: Applying engineering principles to software development
- **Engineering**: Solving problems using scientific knowledge within limited time and cost
- **SDLC**: Software Development Life Cycle

### Software Development Process
A series of activities to implement user requirements into software systems including procedures, methods, tools, and developers.


## 2. Software Development Models

### Build-and-Fix Model
- **Description**: Development without formal guidelines or processes
- **Characteristics**: Simple function organization and development without requirements analysis or design
- **Advantages**: Suitable for single developer, short-term projects
- **Disadvantages**:
  - Lack of documented outputs
  - Difficult maintenance
  - Continuous modification possibilities

### Linear Sequential Model (Waterfall)
- **Description**: Sequential development following standardized processes
- **Characteristics**: Top-down approach, non-parallel, documented results required
- **Procedure**: Planning → Analysis → Design → Implementation → Testing → Maintenance
- **Advantages**: Easy management, systematic documentation, suitable for stable requirements
- **Disadvantages**:
  - Each phase must be completed before next
  - Difficult to verify requirements until final stage
  - High cost for modifications

### Evolutionary Process Model
- **Prototype Model**:
  - Creates initial prototype, repeats modification process
  - Suitable for unclear or changing requirements
  - Advantages: Visual results, progressive requirements definition
  - Disadvantages: Difficult cost estimation, prototype vs final product confusion

- **Spiral Model**:
  - Adds risk analysis to prototype model
  - Process: Requirements analysis → Risk analysis → Prototype → User evaluation
  - Advantages: Risk consideration, high user satisfaction
  - Disadvantages: Long development time, requires risk management expertise

### Phased Development Model
- **Incremental Development**: Developing important parts first, gradually expanding scope
- **Iterative Development**: Developing entire system first, then improving each subsystem

### Unified Process Model
- **Description**: Iterative development for large, complex software
- **Phases**: Inception → Elaboration → Construction → Transition
- **Characteristics**: Flexible response to changing requirements, UML-based

### Agile Process Model
- **Philosophy**: Rapid response to customer needs, solving problems as they arise
- **Agile Values** (2001 Agile Manifesto):
  - Individuals and interactions over processes and tools
  - Working software over comprehensive documentation
  - Customer collaboration over contract negotiation
  - Responding to change over following a plan

### Scrum Framework
- **Components**: Product backlog, Sprint planning, Daily scrum, Sprint review, Sprint retrospective
- **Roles**: Product owner, Scrum master, Development team
- **Artifacts**: Product backlog, Sprint backlog, Burndown chart
- **Advantages**: Regular deliverables, daily coordination, simple methodology
- **Disadvantages**: Requires functional product per sprint, potential meeting overhead


## 3. UML (Unified Modeling Language)

### UML Diagrams
Visual representation of system interactions, structure, and component relationships.

### Use Case Diagram
- **Actor**: Person or system that interacts with the system
- **Use Case**: Functions that users want to use through the system
- **Relationships**: Association, generalization, include, extend

### Class Diagram
- **Components**: Class name, attributes, methods, visibility
- **Relationships**: Association, generalization, aggregation, composition, dependency, realization

### Sequence Diagram
- **Purpose**: Shows object interactions based on message sequence during execution
- **Components**: Objects, lifelines, messages (synchronous, asynchronous, recursive, reply)

### Activity Diagram
- **Purpose**: Represents behavior and activities during execution
- **Components**: Start/end states, activities, transitions, decision points, synchronization bars

### State Diagram
- **Purpose**: Represents state changes of objects
- **Components**: States, transitions, events

### Component Diagram
- **Purpose**: Shows relationships between executable modules
- **Components**: Components, interfaces, dependencies

### Deployment Diagram
- **Purpose**: Defines hardware resources and node relationships
- **Components**: Nodes, hardware allocation


## 4. Planning

### Project Planning Considerations
- Problem definition
- Feasibility analysis
- Software development cost estimation
- Schedule planning
- Risk analysis

### Feasibility Analysis
- **Economic Feasibility**: Cost-benefit analysis, marketability
- **Technical Feasibility**: Technology availability assessment
- **Legal Feasibility**: License verification, intellectual property

### Cost Estimation Methods
- **Top-down Methods**:
  - Expert judgment
  - Delphi technique
- **Bottom-up Methods**:
  - LOC (Lines of Code) method
  - Function point analysis
- **Mathematical Methods**:
  - COCOMO (Constructive Cost Model)
  - COCOMO II

### Function Point Analysis
- **Purpose**: Quantitative measurement of software size based on functional requirements
- **Components**: Internal logical files, external interface files, external inputs/outputs/inquiries
- **Advantages**: User requirement-based, objective measurement, applicable to all development phases
- **Disadvantages**: Requires high analysis skills, needs function point experts

### Schedule Planning
- **WBS (Work Breakdown Structure)**: Dividing project into manageable work packages
- **Network Charts**: PERT/CPM for project scheduling
- **Gantt Charts**: Bar-type scheduling tool

### Risk Analysis
- **Risk Management Process**: Risk identification → Risk analysis → Risk planning → Risk monitoring
- **Risk Assessment**: Probability and impact analysis
- **Risk Response**: Avoidance, mitigation, transfer, acceptance


## 5. Requirements Analysis

### Requirements Definition
- **Functional Requirements**: Functions that users require from the system
- **Non-functional Requirements**: Performance, quality, constraints
  - Quality attributes: Reliability, availability, performance, security, usability

### Requirements Analysis Process
1. Data collection
2. Requirements elicitation
3. Documentation
4. Verification

### Requirements Representation
- **Natural Language**: Easy to understand but may be ambiguous
- **Formal Methods**: Mathematical notation, precise but complex
- **Modeling**: UML diagrams, structured analysis tools

### Structured Analysis Tools
- **Data Flow Diagram (DFD)**: Shows data processing flow
- **Data Dictionary**: Detailed description of data in DFD
- **Process Specification**: Algorithm-based detailed description

### Object-Oriented Analysis
- **Use Case Modeling**: Capturing user requirements
- **Use Case Specification**: Detailed documentation including preconditions, postconditions, event flows

### Requirements Documentation
- **Requirements Specification**: Contract between users and developers
- **Quality Attributes**: Completeness, consistency, clarity, traceability, modifiability, verifiability


## 6. Architecture Design and Class Design
### Design Principles
- **Divide and Conquer**: Breaking complex problems into smaller, manageable parts
- **Abstraction**: Focusing on essential features while hiding implementation details
- **Encapsulation**: Bundling data and methods, hiding internal implementation
- **Information Hiding**: Controlling access to object internals
- **Inheritance**: Reusing and extending existing classes
- **Polymorphism**: Supporting multiple forms through overloading and overriding

### Modularity
- **Module Characteristics**: Independent functionality, unique names, callable by other modules
- **Coupling**: Degree of interdependence between modules (should be loose)
- **Cohesion**: Degree of relatedness within a module (should be strong)

### Coupling Types (Loose to Tight)
- Data coupling
- Stamp coupling
- Control coupling
- Common coupling
- Content coupling

### Cohesion Types (Strong to Weak)
- Functional cohesion
- Sequential cohesion
- Communicational cohesion
- Procedural cohesion
- Temporal cohesion
- Logical cohesion
- Coincidental cohesion

### User Interface Design
- **Interface Types**: CUI, CLI, GUI, NUI
- **Design Principles**: Easy to learn, convenient to use, consistent, efficient, error handling

### Architecture Design
- **Purpose**: Creating software framework and structure
- **Quality Attributes**: Availability, modifiability, performance, security, usability, testability
- **Architecture Styles**:
  - Repository model
  - Client-server style
  - Layered style
  - MVC (Model-View-Controller)
  - Pipe and filter

### Class Design
- **Class Relationships**: Association, generalization, aggregation, composition, dependency, realization
- **SOLID Principles**:
  - Single Responsibility Principle (SRP)
  - Open-Closed Principle (OCP)
  - Liskov Substitution Principle (LSP)
  - Dependency Inversion Principle (DIP)
  - Interface Segregation Principle (ISP)


## 7. Design Patterns

### Pattern Categories
- **Behavioral Patterns**: Strategy, State, Template Method, Observer, etc.
- **Structural Patterns**: Decorator, Adapter, Composite, Facade, etc.
- **Creational Patterns**: Factory Method, Singleton, Prototype, Builder, etc.

### Key Design Patterns
- **Strategy Pattern**: Encapsulating algorithms and making them interchangeable
- **State Pattern**: Changing object behavior based on internal state
- **Decorator Pattern**: Adding responsibilities to objects dynamically
- **Adapter Pattern**: Converting interface to make incompatible classes work together
- **Factory Method Pattern**: Creating objects without specifying exact classes
- **Singleton Pattern**: Ensuring only one instance of a class exists


## 8. Implementation

### Standard Coding Rules
- **Purpose**: Improving readability, maintainability, and development efficiency
- **Naming Conventions**: 31 characters maximum, meaningful names, consistent rules
- **Code Structure**: 200 lines per file, 80 characters per line, proper indentation
- **Comments**: Code information, method descriptions, clear distinction from code
- **Variable Declaration**: Proper initialization, appropriate data types
- **Control Structures**: Proper use of switch, for, if-else statements


## 9. Testing
- Testing
- Necessity and Characteristics of Testing
- Testing Procedures
    - Test Planning
    - Test Case Design
    - Test Execution and Measurement
    - Test Result Analysis
    - Error Tracking and Correction
- Classification of Tests
    - Tests by Perspective
    - Tests by Purpose
    - Tests by Program Execution
- Static Testing
    - Formal Review Procedures
- Dynamic Testing
- Specification-Based Testing
    - Syntax Technique
    - Equivalence Partitioning Technique
    - Boundary Value Analysis Technique
    - Cause-Effect Graphing Technique
- Implementation-Based Testing
    - Statement Coverage Criteria
    - Branch Coverage Criteria / Decision Coverage Criteria
    - Condition Coverage Criteria
    - Branch/Condition Coverage Criteria
    - Multiple Condition Coverage Criteria
    - Basic Path Testing
- Classification of Tests
    - Tests by Software Development Phase


## 10. Quality

### Quality Perspectives
- **User Perspective**: Easy to use, various functions, fast performance
- **Developer Perspective**: Follows coding standards, easy to develop and modify
- **Manager Perspective**: Completed within budget and schedule
- **Maintainer Perspective**: High readability, easy to understand

### Quality Models
- **McCall's Quality Model**: 11 quality factors
  - Product operation: Correctness, efficiency, integrity
  - Product revision: Maintainability, flexibility, testability
  - Product transition: Interoperability, reusability, portability

- **ISO/IEC 9126**: 6 quality characteristics
  - Functionality, reliability, usability, efficiency, maintainability, portability

### Quality Standards
- **ISO/IEC 14598**: Software product evaluation
- **ISO/IEC 12119**: Package software quality requirements
- **ISO/IEC 25000 (SQuaRE)**: Integrated quality evaluation standard

### Process Quality Models
- **ISO 9000**: Quality management systems
- **ISO 12207**: Software lifecycle processes
- **CMMI**: Capability Maturity Model Integration
  - 5 maturity levels: Initial, Managed, Defined, Quantitatively Managed, Optimizing
- **SPICE (ISO 15504)**: Software process improvement and capability determination

### Quality Management
- **Quality Control**: Defining processes and standards for developers to follow
- **Quality Assurance**: Systematic activities to ensure quality throughout development


## 11. Project Management
- Project
- Project Management
- Example of Configuration Management
- Configuration Management
- Maintenance
