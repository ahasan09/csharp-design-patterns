# Design Pattern

Gang-of-Four (GoF) design patterns implemented in C# as a .NET solution.

## Tech Stack
- C# / .NET Framework (legacy 4.x `.csproj`)
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
# Build from CLI (MSBuild)
msbuild GofPattern/<solution>.sln
```
Or open the `.sln` file in Visual Studio. Modern `dotnet build` will not work on these legacy `.csproj` files.

## Key Notes
- Covers creational, structural, and behavioral GoF patterns.
