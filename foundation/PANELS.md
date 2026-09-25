# PANELS — the grammar and the ledger of every line the Ledger ever prints

v1.0, 2026-09-25. The Panel Law: cold, quiet, at key beats only — and the
FULL status panel at every gate (night one, rank-ups, year-ends). Digits
live here and in the prose panels only, never loose in narration.

## The grammar (every form)

`「Martial Soul — Name」` · `「Level — N」` · `「Slots: N / N / N」` ·
`「Technique — Name: NN%」` · `「Soul Ring — Beast: N years」` ·
`「Skill — Name: NN%」` · `「Bloodline — Line: NN%」` · life-skill lines `「Name: NN%」`

**THE TWO TIERS (F7 — the full thing in the status):** the FULL status
panel — printed at every gate (night one, rank-ups, year-ends) — carries
every line COMPLETE: the martial soul's class, system, and attribute
(`「Martial Soul — Wolf · beast-type · Power Attack · ice」`), the skill's
nature (`「Skill — The Wolf: 1% · possession · strength, speed, senses, claws」`),
the bloodline's attribute and its work (`「Bloodline — Grey Wolf: 7% · ice
· the body-line: vitality, recovery, the wolf's frame」`). Beat-panels — a
single moving line at a beat — stay short. A bare name and a number is
never the whole status again.

## THE FIRST PANEL — printed (Chapter 1, night one)

The full block, as `STATUS.md` carries it:

> 「Martial Soul — Wolf · beast-type · Power Attack · ice」
> 「Level — 1 · innate 1」
> 「Slots: 1 / 1 / 1」
> 「Technique — Basic Soul Power Cultivation: 1% · the engine, passive」
> 「Technique — The Hunter's Craft: 11% · parked, unslotted」
> 「Skill — The Wolf: 1% · possession · strength, speed, senses, claws」
> 「Bloodline — Grey Wolf: 7% · ice · the body-line: vitality, recovery, the wolf's frame」
> 「Hunter's Sense: 13%」
> 「Plain Speech: 21%」
> 「Mountain Stride: 9%」
> 「The Tally: 27%」

## Chapter ledger (a row per line, per chapter — begins with Chapter 1)

### Chapter 1 — The Grey Wolf (age 6)

| Panel | Beat |
|---|---|
| 「Martial Soul — Wolf · beast-type · Power Attack · ice」 | THE FULL PANEL — the Ledger waking, night one |
| 「Level — 1 · innate 1」 | 〃 |
| 「Slots: 1 / 1 / 1」 | 〃 |
| 「Technique — Basic Soul Power Cultivation: 1% · the engine, passive」 | 〃 |
| 「Technique — The Hunter's Craft: 11% · parked, unslotted」 | 〃 |
| 「Skill — The Wolf: 1% · possession · strength, speed, senses, claws」 | 〃 |
| 「Bloodline — Grey Wolf: 7% · ice · the body-line: vitality, recovery, the wolf's frame」 | 〃 |
| 「Hunter's Sense: 13%」 | 〃 |
| 「Plain Speech: 21%」 | 〃 |
| 「Mountain Stride: 9%」 | 〃 |
| 「The Tally: 27%」 | 〃 |
| 「Technique — Basic Soul Power Cultivation: 2%」 | the dawn reading — the engine's first night |

### Chapter 2 — The Quiet Climb (age 6→7, the first year)

| Panel | Beat |
|---|---|
| 「Level — 2」 | midwinter — the beat panel, short: the water standing higher |
| 「Martial Soul — Wolf · beast-type · Power Attack · ice」 | THE YEAR LIST — the anniversary, every line complete |
| 「Level — 3 · innate 1」 | 〃 |
| 「Slots: 1 / 1 / 1」 | 〃 |
| 「Technique — Basic Soul Power Cultivation: 14% · the engine, passive」 | 〃 |
| 「Technique — The Hunter's Craft: 19% · parked, unslotted」 | 〃 |
| 「Skill — The Wolf: 9% · possession · strength, speed, senses, claws」 | 〃 |
| 「Bloodline — Grey Wolf: 12% · ice · the body-line: vitality, recovery, the wolf's frame」 | 〃 |
| 「Hunter's Sense: 19%」 | 〃 |
| 「Stillness: 6%」 | the new line — surfaced the night the thorn thicket taught it |
| 「Plain Speech: 23%」 | 〃 |
| 「Mountain Stride: 15%」 | 〃 |
| 「The Tally: 29%」 | 〃 |

## The law of this file

Every panel line that prints in a chapter must exist here, and every row
here must exist in a chapter — `tools/check_panels.py` enforces it both
ways, and a frozen or stale meter fails the build.
