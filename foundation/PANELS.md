# PANELS — the grammar and the ledger of every line the Ledger ever prints

v1.0, 2026-09-25. The Panel Law: cold, quiet, at key beats only — and the
FULL status panel at every gate (night one, rank-ups, year-ends). Digits
live here and in the prose panels only, never loose in narration.

## The grammar (every form)

`「Martial Soul — Name」` · `「Level — N」` · `「Slots: N / N / N」` ·
`「Technique — Name: NN%」` · `「Soul Ring — Beast: N years」` ·
`「Skill — Name: NN%」` · `「Bloodline — Line: NN%」` · life-skill lines
`「Name: NN%」`

## THE FIRST PANEL (defined, not yet printed — Chapter 1, night one)

The full block, as `STATUS.md` carries it:

> 「Martial Soul — Grey Wolf」
> 「Level — 1」
> 「Slots: 1 / 1 / 1」
> 「Technique — Basic Soul Power Cultivation: 1%」
> 「Technique — The Hunter's Craft: 11%」
> 「Skill — The Wolf: 1%」
> 「Bloodline — Grey Wolf: 7%」
> 「Senses: 13%」
> 「Speech: 21%」
> 「Walking and Running: 9%」
> 「Counting: 27%」

## Chapter ledger (a row per line, per chapter — begins with Chapter 1)

*(empty — the chapters have not begun)*

## The law of this file

Every panel line that prints in a chapter must exist here, and every row
here must exist in a chapter — `tools/check_panels.py` enforces it both
ways, and a frozen or stale meter fails the build.
