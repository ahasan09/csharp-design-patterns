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

- C# / .NET 8 (SDK-style projects targeting `net8.0`)
- Visual Studio solution (`.sln`)

> Note: The projects were migrated from legacy .NET Framework (`ToolsVersion` 4.0)
> `.csproj` files to SDK-style .NET 8 projects. The migration was done without a
> local compilation step, so if you hit any build issue please report it.

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) 8.0 or later, **or**
- [Visual Studio](https://visualstudio.microsoft.com/) 2022 (17.8+)

## Getting Started

### Using .NET CLI

```bash
git clone https://github.com/ahasan09/csharp-design-patterns
cd csharp-design-patterns/GofPattern
dotnet build DesignPatterns.sln
dotnet run --project Singleton/
# any other pattern works the same way, e.g.
dotnet run --project Observer/
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
