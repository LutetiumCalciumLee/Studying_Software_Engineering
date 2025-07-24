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
## 5. Design
- Design
- Design Principles
    - Divide and Conquer
    - Abstraction
    - Encapsulation
    - Information Hiding
    - Inheritance
    - Polymorphism
- Modularity
- Module Evaluation Criteria
    - Cohesion
    - Coupling
- User Interface Design

## 6. Architecture Design and Class Design
- Architecture Design
- Architecture Quality Attributes
    - SAiP
- 4+1 View of Architecture
- Architectural Styles
    - Data-Centered Style / Repository Model
    - Client-Server Style
    - Layered Style
    - MVC Style
    - Data Flow Style / Pipe and Filter
- Relationships Between Classes
    - Association
    - Generalization
    - Aggregation
    - Composition
    - Dependency
    - Realization
    - Single Responsibility Principle
    - Open-Closed Principle
    - Liskov Substitution Principle
    - Dependency Inversion Principle
    - Interface Segregation Principle

## 7. Design Patterns
- Design Patterns
    - Efficiency Through Use of Past Cases and Experience
- Behavioral Patterns
    - Strategy Pattern
    - State Pattern
- Structural Patterns
    - Decorator Pattern
    - Adapter Pattern
- Creational Patterns
    - Factory Method
    - Singleton Pattern

## 8. Implementation
- Necessity of Standard Coding Rules
- Main Standard Coding Rules
    - Naming
    - Source
    - Comments
    - Variable Declaration and Data Types
    - Constants
    - Expressions
    - Statements

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
- Quality
- Quality by Perspective
- Quality Objectives
- Quality Factors
    - McCall’s Quality Factors
- Quality Evaluation Standard Model
- Product Quality Attribute Evaluation Model
- Process Quality Attribute Evaluation Model
- Representative Process Capability Evaluation Models
    - CMMI (Capability Maturity Model Integration)
    - SPICE (Software Process Improvement and Capability dEtermination)
- Quality Management

## 11. Project Management
- Project
- Project Management
- Example of Configuration Management
- Configuration Management
- Maintenance
