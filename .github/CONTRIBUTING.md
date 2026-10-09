# Contributing to FreeDotnetFonts

FreeDotnetFonts is a community-maintained fork of SixLabors.Fonts 1.0.1. Its goal is to keep the 1.0.x API available under the Apache License 2.0, with security and compatibility fixes.

## Scope

- Security fixes, bug fixes and dependency updates for the 1.0.x API are welcome.
- New features are only accepted if they don't break binary compatibility. The assembly name (`SixLabors.Fonts`), assembly version (1.0.0.0) and public API stay the same, so the package remains a drop-in replacement.

## Licensing of contributions

- All contributions are licensed under the [Apache License 2.0](../LICENSE).
- **Do not copy code from SixLabors.Fonts 2.0 or later.** Those versions use the Six Labors Split License, which is not compatible with this project. Fixes for issues that were also fixed upstream must be written independently.
- Keep the existing copyright headers in files you change. You may add your own line below them.

## Building and testing

```
dotnet build -c Release
dotnet test tests/SixLabors.Fonts.Tests/SixLabors.Fonts.Tests.csproj -c Release -f net8.0
```

## Reporting security issues

Do not open a public issue. Use GitHub's private vulnerability reporting on this repository.
