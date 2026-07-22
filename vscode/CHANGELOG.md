# Change Log

All notable changes to the "nordlys" extension will be documented in this file.

## [0.1.0] 2026-07-22

- String interpolation delimiters hue-shifted from deep green #63C56B to mint-teal #4EC9B0 for clearer separation from string green #7EE787 (Rider port updated to match)
- Nordlys-native terminal ANSI palette replacing the stock VS Code primaries: red #E06C75, green #63C56B, yellow #E5C07B (gold), blue #6395C5, magenta #D688D4, cyan #3BA6C4; bright variants from palette colors (#7EE787, #B6DDFD, #1CB7E3, #5C6370) or +20% white
- Terminal surfaces aligned with the Windows Terminal port: background #1A1B1C (was panel #212223), cursor #D4D4D4, selection #404859
- Extension icon: painterly aurora over a polar ocean in the spirit of The Starry Night, brushed entirely from theme colors
- README: color swatch images in the palette rundown, visible on GitHub and the Marketplace page
- Repo: live terminal section in the preview page (reads the Windows Terminal scheme), VS Code task and launch config to serve and open the preview

## [0.0.1] 2026-07-22

Initial release. Nordlys grew out of [Nightworlds](https://github.com/feafarot/nightworlds) and keeps its cool, low-contrast character while committing to an aurora-over-polar-night palette:

- Workbench surfaces derived from VS Code Default Dark 2026, lifted +8 per channel for lower text/background contrast (editor #1A1B1C, chrome #212223, widgets #28292A, line highlight #2C2D2E, borders #323334)
- Aurora-green literals: strings and constants #7EE787, numbers #93EB9B, string interpolation #63C56B
- Quiet callables: method/function calls near-foreground #DDE3EA, declarations bold; bright blue reserved for links, diff headers and info tokens
- Namespaces, variables and parameters plain #D4D4D4; properties and fields #B6DDFD; types #1CB7E3; interfaces #3BA6C4; decorators #E5C07B
- JSON property names keyword blue #6395C5, matching YAML keys
- Full semantic token coverage: all 24 standard token types, deprecated -> strikethrough, F# mutable -> underline, plus the C# extension's custom types (controlKeyword, field, constant, records, delegates, verbatim strings, embedded regex/JSON, XML doc comments, Razor markup) and Ionide F# (cexpr, extension methods)
- Muted bracket-pair colors, barely visible whitespace markers (#8C8C8C1A), orange debugging status bar
