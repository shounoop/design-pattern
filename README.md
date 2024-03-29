# design-pattern
## I. Overview
  Design patterns are reusable solutions to common problems that software encounter while designing and developing software applications.
  These patterns provide a standard approach to solve a particular problem, which has been proven over time to be effective and efficient.
  
- There are three types of design patterns:
  ### 1. Creational Patterns
    - These patterns are used to create objects in a way that is suitable for a particular situation.
    - Examples of creational patterns incluse: Singleton, Factory Method, Abstract Factory, Builder, and Prototype.
    
  ### 2. Structural Patterns
    - These patterns are used to provide a way to organize objects in a particular structure.
    - Examples of structural patterns include: Adapter, Bridge, Composite, Decorator, Facade, Flyweight, and Proxy.
  
  ### 3. Behavioral Patterns
    - These patterns are used to manage communication and behavior between objects in a system.
    - Examples of behavioral patterns incluse: Chain of Responsibility, Command, Interpreter, Iterator, Mediator, Memento, Observe, State, Strategy, Template Method, and Visitor.

--> Design patterns are a valuable tool for software developers as they provide proven solutions to common problems. 
--> By using design patterns, developers can save time and effort, reduce errors, and improve the quanlity of their software applications.

## II. Detail
### 1. Creational Patterns
#### 1.1. Factory Pattern
  - This pattern is used to create objects without specifying the exact class of object that will be created.
  - The basic idea is to define an interface for creating objects, but allow subclasses to decide which class to instantiate.
  --> The factory pattern provides an elegant way to encapsulate object creation logic and make code more modular and flexible.
  --> It also helps to decouple client code from concrete classes, making it easier to change the implementation of the interface without affecting the client code.
  
### 2. Structural Patterns
#### 2.1. Adapter Pattern
  - This pattern allows imcompatible interfaces to work together by wrapping an existing class with a new interface that client code can use.
  
#### 2.2. Bridge Pattern
  - This pattern decouples an abstraction from its implementation so that they can vary independently.
  - It involves using an interface or abtract class to separate the implementation from the abstraction.

#### 2.3. Composite Pattern
  - This pattern is used to represent part-whole hierarchies of objects.
  - It allows clients to treat individual objects and groups of objects uniformly.
  - In other words, the Composite pattern allows you to treat a single object or a group of objects in the same way.
  
#### 2.4. Decorator Pattern
  - This pattern allows for dynamic behavior modification
  
#### 2.5. Facade Pattern
  - This pattern simplifies complex systems

#### 2.6. Flyweight Pattern
  - This pattern reduces memory usage by sharing common data

