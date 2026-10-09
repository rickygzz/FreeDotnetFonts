# FreeDotnetFonts

[![License: Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)

**FreeDotnetFonts is a community-maintained fork of [SixLabors.Fonts](https://github.com/SixLabors/Fonts) 1.0.1, the last release published under the Apache License 2.0.** SixLabors.Fonts 2.0 and later use the Six Labors Split License. This fork keeps the 1.0.x API available under Apache-2.0 and is the place for future fixes. It is used by [FreeDotnetPOI](https://github.com/rickygzz/FreeDotnetPOI).

The assembly name (`SixLabors.Fonts`), strong-name identity (version 1.0.0.0) and namespaces are unchanged, so it is a drop-in replacement for `SixLabors.Fonts` 1.0.x:

```
dotnet add package FreeDotnetFonts
```

Do not reference both `FreeDotnetFonts` and `SixLabors.Fonts` in the same project.

## Changes from SixLabors.Fonts 1.0.1

| Version | Change |
|---|---|
| 1.0.2 | First release of the fork. No functional changes; package metadata and repository infrastructure updated. |

This project is not affiliated with or endorsed by Six Labors. All credit for the original work goes to Six Labors and the Fonts contributors. No code from SixLabors.Fonts 2.0 or later (Six Labors Split License) is included. See [NOTICE](NOTICE).

## About

SixLabors.Fonts is a cross-platform library for loading fonts (TrueType, OpenType, WOFF, WOFF2) and for laying out and measuring text. It targets .NET Standard 2.0/2.1 and .NET Core 3.1, so it runs on any modern .NET version. The API is identical to SixLabors.Fonts 1.0.x.

## Building

```
dotnet build -c Release
dotnet test tests/SixLabors.Fonts.Tests/SixLabors.Fonts.Tests.csproj -c Release -f net10.0
```

## Contributing

See [CONTRIBUTING.md](.github/CONTRIBUTING.md). Contributions must not include code from SixLabors.Fonts 2.0 or later.

## License

Licensed under the [Apache License 2.0](LICENSE). See [NOTICE](NOTICE).
