# VOCK-FO2
Vocal Output Creation Kit for Fallout 2

Toolkit and asset pipeline for adding voiced dialogue to Fallout 2 NPCs, from recorded line to in-game lip-synced audio.

## Structure

| Path | Contents |
|------|----------|
| `characters.py` | Character table: MSG file stem, audio tag prefix, SSL script stem(s), and talking head name(s) for every voiced NPC |
| `txt/` | Line scripts, one file per line (source text to be recorded) |
| `wav/` | Recorded audio (16-bit PCM, mono, 22050 Hz) |
| `textgrid/` | Praat word/phoneme alignment for each recording |
| `lip/` | Compiled lip-sync data derived from the alignment |
| `acm/` | Final compressed audio in Fallout 2's ACM format |
| `msg/` | Extracted per-character dialogue MSG files |
| `scripts_src/` | SSL dialogue script source for characters with custom logic |
| `scripts/` | Compiled INT scripts |
| `va-scripts/` | Per-character VA line scripts, standardized template (title, character, Direction, scene-grouped lines) |
| `npc_filter.cfg` | Optional NPC prefix allowlist to limit processing to specific characters |
| `float_filter.cfg` | Float (combat/ambient) message tag ranges per character |
| `THAT.md` | Voice actor reference pulled from public casting call listings |
| `CREDITS.md` | Cast and contributor links |
| `CHANGELOG.md` | Version history |

Filename prefixes (`arth`, `kaga`, `zaius`, etc.) match the `prefix` field in `characters.py` and tie each character's txt/wav/textgrid/lip/acm files together.
