# Design Pattern

Gang-of-Four (GoF) design patterns implemented in C# as a .NET solution.

## Tech Stack
- C# / .NET 8 (SDK-style `.csproj`, `net8.0`)
- Visual Studio solution (.sln)

## Project Structure
```
GofPattern/
├── *.sln                  # Visual Studio solution file
└── <PatternName>/
    └── *.cs               # Pattern implementation
```

## Development
```bash
# Build from CLI
dotnet build GofPattern/DesignPatterns.sln

# Run a single pattern project
dotnet run --project GofPattern/Singleton/
```
Or open the `.sln` file in Visual Studio 2022+.

## Key Notes
- Covers creational, structural, and behavioral GoF patterns.
