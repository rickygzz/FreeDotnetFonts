# FreeDotnetFonts

FreeDotnetFonts is a community-maintained fork of [SixLabors.Fonts](https://github.com/SixLabors/Fonts) 1.0.1, the last release published under the Apache License 2.0. SixLabors.Fonts 2.0 and later use the Six Labors Split License; this fork keeps the 1.0.x API free.

## Drop-in replacement

The assembly name (`SixLabors.Fonts`), strong-name identity (version 1.0.0.0), namespaces and public API are unchanged. Replace the package reference and your code keeps working:

```
dotnet remove package SixLabors.Fonts
dotnet add package FreeDotnetFonts
```

Do not reference both `FreeDotnetFonts` and `SixLabors.Fonts` in the same project.

## License and credits

Licensed under the [Apache License 2.0](https://github.com/rickygzz/FreeDotnetFonts/blob/main/LICENSE). All credit for the original work goes to Six Labors and the Fonts contributors. This project is not affiliated with or endorsed by Six Labors. No code from SixLabors.Fonts 2.0 or later (Six Labors Split License) is included.

Source, issues and security reports: https://github.com/rickygzz/FreeDotnetFonts
