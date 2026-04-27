# C# Design Patterns

Comprehensive implementations of Gang of Four (GoF) design patterns in C#. Written in Bangla comments for Bengali-speaking developers learning OOP design patterns.

## Patterns Implemented

### Creational
- Abstract Factory
- Builder
- Factory Method
- Prototype
- Singleton

### Structural
- Adapter
- Bridge
- Composite
- Decorator
- Facade
- Flyweight
- Proxy (via Null Object Pattern)

### Behavioral
- Chain of Responsibility
- Command
- Mediator
- Memento
- Observer
- State
- Strategy
- Template Method
- Visitor

## Tech Stack

- C# / .NET
- Visual Studio solution (`.sln`)

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) 4.x or later, **or**
- [Visual Studio](https://visualstudio.microsoft.com/) 2019+

## Getting Started

### Using .NET CLI

```bash
git clone https://github.com/ahasan09/csharp-design-patterns
cd csharp-design-patterns/GofPattern
dotnet build DesignPatterns.sln
dotnet run --project Singleton/
```

### Using Visual Studio

1. Open `GofPattern/DesignPatterns.sln` in Visual Studio
2. Set the desired pattern project as the startup project
3. Press **F5** to run

## Project Structure

```
GofPattern/
├── Singleton/
├── FactoryMethod/
├── AbstracFactory/
├── Builder/
├── Prototype/
├── Adaptor/
├── BridgePattern/
├── CompositeDesignPattern/
├── Decorator/
├── FacadePattern/
├── FlyWeight/
├── ChainofResponsibility/
├── CommandPattern/
├── MediatorPattern/
├── Memento/
├── NullObjectPattern/
├── Observer/
├── StateDesignPattern/
├── Strategy/
├── TempletMethod/
└── VisitorDesignPattern/
```
