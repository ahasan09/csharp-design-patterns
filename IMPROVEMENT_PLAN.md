# Improvement Plan: designpattern

## Overview
GoF design patterns in C#. Good reference material but likely targets an older .NET version, has no automated tests, and only covers a subset of the 23 GoF patterns.

## Improvements

### Modernization
- Target .NET 9 (LTS) — use modern C# features (records, pattern matching, primary constructors) to show idiomatic modern implementations alongside the classic versions
- Add a `global.json` pinning the .NET SDK version for reproducibility
- Add a `dotnet-tools.json` for any local tools used

### Complete GoF Coverage
- Audit which of the 23 GoF patterns are implemented and add any missing ones
- Add behavioral patterns if missing: Chain of Responsibility, Command, Iterator, Mediator, Memento, Observer, State, Strategy, Template Method, Visitor

### Testing
- Add xUnit unit tests for each pattern demonstrating its behavior and the problem it solves
- Each test should document the "problem without the pattern" and "solution with the pattern" in test names

### Documentation
- Add an XML doc comment (`<summary>`) to each pattern class explaining when to use it
- Add a root `README.md` listing all patterns with a one-line description and a real-world use case example

### Code Quality
- Enable nullable reference types (`<Nullable>enable</Nullable>`) and treat warnings as errors
- Add `.editorconfig` for consistent code style
- Add GitHub Actions CI: `dotnet build` + `dotnet test` on every push
