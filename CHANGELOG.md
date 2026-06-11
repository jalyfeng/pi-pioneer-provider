# Changelog

All notable changes to this project will be documented in this file.

## [0.2.0]

<!-- USER-EDITABLE SECTION START -->
Pioneer 1.1.4 compatibility release.

**Highlights:**
- Adds `pioneer/auto` router model (not exposed via `/base-models`, limits derived dynamically from max of all discoverable models — currently 1M context / 131k max tokens)
- New models auto-discovered from `/base-models`: Claude Fable 5, Nemotron 3 Nano/Super/Ultra, Mimo V2.5/Pro, Gemma 4 12B IT
- Disables Pioneer inference retention by sending `store: false` on every request (`compat.supportsStore: true`)
- Published under the `@cad0p` npm scope
- TypeScript type checking configured (`noEmit: true` for type stripping)
<!-- USER-EDITABLE SECTION END -->

## [0.1.0]

<!-- USER-EDITABLE SECTION START -->
Initial release of the `@cad0p` fork of `pi-pioneer-provider`.

**Highlights:**
- Disables Pioneer inference retention by sending `store: false` on every request (`compat.supportsStore: true`)
- Published under the `@cad0p` npm scope
<!-- USER-EDITABLE SECTION END -->
