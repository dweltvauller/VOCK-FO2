# VOCK — Recording Directions for Voice Actors

General instructions for recording lines for this project. Read this once before your first session; your character-specific script (e.g. `Krom.md`) has the actual lines.

## How to read your script

- The **Direction** blurb at the top sets the voice for the *entire* character — tone, accent, age, energy. Keep it consistent across every line, even lines recorded in separate sessions.
- Each **Context** note under a heading tells you when that line plays in-game. It's for your understanding only — don't read it aloud.
- Text in `[brackets]` or `(parentheses)` is staged/stage direction (a gesture, an action, a price the game fills in) — not dialogue. Don't voice it. If a bracket appears mid-sentence, only the words outside it are spoken.
- Numbered lines grouped under one heading are usually alternate variants of the same moment (different PC sex, stat check, or phrasing) — record each one as its own full take. Don't reuse a single take across variants.

## File specs

- One audio file per line. Name the file exactly after its tag — the short code right before the colon (e.g. `krom14: [...] Gladly...` → `krom14.wav`).
- Record clean and dry: single speaker, no music, no reverb/effects, minimal room noise. Audio gets normalized automatically (mono, 16-bit, 22050 Hz) on our end, so don't worry about matching that exactly — just start from a clean source.
- Leave a small amount of natural silence before and after each line (don't hard-cut on the first/last word), but no long dead air — the timing engine aligns lip-sync directly from the file.
- Don't punch in or edit mid-line. If you flub it, re-record the whole take.

## Delivery

- Perform to the Direction blurb, not to how the line reads on the page in isolation — some lines are blunt or terse in text but should still land as that character.
- Keep pacing natural and conversational; avoid over-enunciating or leaving unnaturally long pauses between clauses, since the alignment step times lip movement to your actual speech.
- If a line trails off (e.g. ends mid-sentence before a game-inserted value like a price), let it trail off naturally rather than sounding cut short.

## Submitting

- Deliver one folder per character, named after the character, containing all their numbered WAV files flat (no subfolders).
