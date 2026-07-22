# Nordlys

Aurora over polar ocean night.

A dark, low-contrast VS Code theme built around the aurora borealis: green literals on a neutral graphite night sky, cool blue structure, and rare warm accents. Named after the Norwegian word for the northern lights.

## Character

- **Polar night surfaces.** Neutral graphite backgrounds with no blue cast (editor ![#1A1B1C](https://raw.githubusercontent.com/feafarot/Nordlys/main/palette/swatches/1A1B1C.png) `#1A1B1C`, chrome ![#212223](https://raw.githubusercontent.com/feafarot/Nordlys/main/palette/swatches/212223.png) `#212223`), derived from VS Code's Default Dark 2026 and lifted slightly to reduce text/background contrast for long sessions.
- **Aurora greens.** Strings and constants ![#7EE787](https://raw.githubusercontent.com/feafarot/Nordlys/main/palette/swatches/7EE787.png) `#7EE787` (the 557.7nm oxygen line, more or less), numbers a step lighter ![#93EB9B](https://raw.githubusercontent.com/feafarot/Nordlys/main/palette/swatches/93EB9B.png) `#93EB9B`, interpolation delimiters hue-shifted to mint-teal ![#4EC9B0](https://raw.githubusercontent.com/feafarot/Nordlys/main/palette/swatches/4EC9B0.png) `#4EC9B0` so they stand out inside green strings.
- **Quiet callables.** Method and function calls sit near the foreground (![#DDE3EA](https://raw.githubusercontent.com/feafarot/Nordlys/main/palette/swatches/DDE3EA.png) `#DDE3EA`); declarations are bold for wayfinding. No shouting call sites.
- **Plain identifiers.** Variables, parameters and namespaces stay at default foreground; properties and fields get a soft sky blue ![#B6DDFD](https://raw.githubusercontent.com/feafarot/Nordlys/main/palette/swatches/B6DDFD.png) `#B6DDFD`; types are cyan ![#1CB7E3](https://raw.githubusercontent.com/feafarot/Nordlys/main/palette/swatches/1CB7E3.png) `#1CB7E3`.
- **Full semantic token coverage.** All 24 standard semantic token types plus the C# extension's custom classifications (records, delegates, embedded regex/JSON, XML doc comments, Razor) and Ionide F# (`cexpr`, mutable underline).
- **Rare warm accents.** Gold decorators, magenta escapes, red macros, and an orange status bar while debugging.

## Companion ports

The [Nordlys repository](https://github.com/feafarot/Nordlys) also ships the palette for other tools, including JetBrains Rider and Windows Terminal (more to come?)
