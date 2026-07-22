# Change Log

All notable changes to the "nordlys" extension will be documented in this file.

## [0.0.1] 2026-07-22

Initial release. Nordlys grew out of [Nightworlds](https://github.com/feafarot/nightworlds) and keeps its cool, low-contrast character while committing to an aurora-over-polar-night palette:

- Workbench surfaces derived from VS Code Default Dark 2026, lifted +8 per channel for lower text/background contrast (editor #1A1B1C, chrome #212223, widgets #28292A, line highlight #2C2D2E, borders #323334)
- Aurora-green literals: strings and constants #7EE787, numbers #93EB9B, string interpolation #63C56B
- Quiet callables: method/function calls near-foreground #DDE3EA, declarations bold; bright blue reserved for links, diff headers and info tokens
- Namespaces, variables and parameters plain #D4D4D4; properties and fields #B6DDFD; types #1CB7E3; interfaces #3BA6C4; decorators #E5C07B
- JSON property names keyword blue #6395C5, matching YAML keys
- Full semantic token coverage: all 24 standard token types, deprecated -> strikethrough, F# mutable -> underline, plus the C# extension's custom types (controlKeyword, field, constant, records, delegates, verbatim strings, embedded regex/JSON, XML doc comments, Razor markup) and Ionide F# (cexpr, extension methods)
- Muted bracket-pair colors, barely visible whitespace markers (#8C8C8C1A), orange debugging status bar
