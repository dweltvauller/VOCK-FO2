# VOCK-FO2
Vocal Output Creation Kit for Fallout 2

Toolkit and asset pipeline for adding voiced dialogue to Fallout 2 NPCs, from recorded line to in-game lip-synced audio.

## Pipeline

Each dialogue line moves through these stages, identified by a shared filename stem (e.g. `arth1`):

1. **`txt/`** - line script, one file per line (source text to be recorded)
2. **`wav/`** - recorded audio (16-bit PCM, mono, 22050 Hz)
3. **`textgrid/`** - Praat word/phoneme alignment for the recording
4. **`lip/`** - compiled lip-sync data derived from the alignment
5. **`acm/`** - final compressed audio in Fallout 2's ACM format

## Structure

| Path | Contents |
|------|----------|
| `characters.py` | Character table: MSG file stem, audio tag prefix, SSL script stem(s), and talking head name(s) for every voiced NPC |
| `msg/` | Extracted per-character dialogue MSG files |
| `scripts_src/` | SSL dialogue script source for characters with custom logic |
| `scripts/` | Compiled INT scripts |
| `list/heads.lst` | Talking head list |
| `list/scripts.lst` | Game script list |
| `CREDITS.md` | Cast and contributor links |
| `CHANGELOG.md` | Version history |

Filename prefixes (`arth`, `kaga`, `zaius`, etc.) match the `prefix` field in `characters.py` and tie each character's txt/wav/textgrid/lip/acm files together.
