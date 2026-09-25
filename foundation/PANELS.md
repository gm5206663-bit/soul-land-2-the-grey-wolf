# PANELS — the grammar and the ledger of every line the Ledger ever prints

v1.0, 2026-09-25. The Panel Law: cold, quiet, at key beats only — and the
FULL status panel at every gate (night one, rank-ups, year-ends). Digits
live here and in the prose panels only, never loose in narration.

## The grammar (every form)

`「Martial Soul — Name」` · `「Level — N」` · `「Slots: N / N / N」` ·
`「Technique — Name: NN%」` · `「Soul Ring — Beast: N years」` ·
`「Skill — Name: NN%」` · `「Bloodline — Line: NN%」` · life-skill lines `「Name: NN%」`

**THE GRADE LADDER (F9 — rank in everything, canon-verified):** every
graded line carries its grade — **Low (Waste) · Mid (Ordinary) · High
(Excellent) · Top (Top-tier) · Ultimate (Divine/Extreme)** — canon's own
quality ladder (receipt 17: "The quality of a Martial Soul ranges from low
to high, including Waste Soul, Ordinary Soul, Excellent Soul, Top-tier
Soul, Divine Soul"). Rings grade by their own ladder (the years: white →
yellow → purple → black → red). Life-skills carry no grade — life has no
ceiling. The level and the slots are counts, not things.

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

> 「Martial Soul — Wolf · beast-type · Power Attack · ice · Mid」
> 「Level — 1 · innate 1」
> 「Slots: 1 / 1 / 1」
> 「Technique — Basic Soul Power Cultivation: 1% · the engine, passive · Low」
> 「Technique — The Hunter's Craft: 11% · parked, unslotted · Low」
> 「Skill — The Wolf: 1% · possession · strength, speed, senses, claws · Mid」
> 「Bloodline — Grey Wolf: 7% · ice · the body-line: vitality, recovery, the wolf's frame · Low」
> 「Hunter's Sense: 13%」
> 「Plain Speech: 21%」
> 「Mountain Stride: 9%」
> 「The Tally: 27%」

## Chapter ledger (a row per line, per chapter — begins with Chapter 1)

### Chapter 1 — The Grey Wolf (age 6)

| Panel | Beat |
|---|---|
| 「Martial Soul — Wolf · beast-type · Power Attack · ice · Mid」 | THE FULL PANEL — the Ledger waking, night one |
| 「Level — 1 · innate 1」 | 〃 |
| 「Slots: 1 / 1 / 1」 | 〃 |
| 「Technique — Basic Soul Power Cultivation: 1% · the engine, passive · Low」 | 〃 |
| 「Technique — The Hunter's Craft: 11% · parked, unslotted · Low」 | 〃 |
| 「Skill — The Wolf: 1% · possession · strength, speed, senses, claws · Mid」 | 〃 |
| 「Bloodline — Grey Wolf: 7% · ice · the body-line: vitality, recovery, the wolf's frame · Low」 | 〃 |
| 「Hunter's Sense: 13%」 | 〃 |
| 「Plain Speech: 21%」 | 〃 |
| 「Mountain Stride: 9%」 | 〃 |
| 「The Tally: 27%」 | 〃 |
| 「Technique — Basic Soul Power Cultivation: 2%」 | the dawn reading — the engine's first night |

### Chapter 2 — The Quiet Climb (age 6→7, the first year)

| Panel | Beat |
|---|---|
| 「Level — 4」 | midwinter — the beat panel, short: the water standing higher |
| 「Martial Soul — Wolf · beast-type · Power Attack · ice · Mid」 | THE YEAR LIST — the anniversary, every line complete |
| 「Level — 9 · innate 1」 | 〃 |
| 「Slots: 1 / 1 / 1」 | 〃 |
| 「Technique — Basic Soul Power Cultivation: 22% · the engine, passive · Low」 | 〃 |
| 「Technique — The Hunter's Craft: 19% · parked, unslotted · Low」 | 〃 |
| 「Skill — The Wolf: 9% · possession · strength, speed, senses, claws · Mid」 | 〃 |
| 「Bloodline — Grey Wolf: 12% · ice · the body-line: vitality, recovery, the wolf's frame · Low」 | 〃 |
| 「Hunter's Sense: 19%」 | 〃 |
| 「Stillness: 6%」 | the new line — surfaced the night the thorn thicket taught it |
| 「Plain Speech: 23%」 | 〃 |
| 「Mountain Stride: 15%」 | 〃 |
| 「The Tally: 29%」 | 〃 |

### Chapter 3 — The Wall (ages 7→10, the wall years)

| Panel | Beat |
|---|---|
| 「Level — 10」 | THE WALL — the count standing still, one line: the water against the stone |
| 「Martial Soul — Wolf · beast-type · Power Attack · ice · Mid」 | THE HUNT-YEAR GATE — the eve panel, every line complete |
| 「Level — 10 · innate 1 · the wall, held three years」 | 〃 |
| 「Slots: 1 / 1 / 1」 | 〃 |
| 「Technique — Basic Soul Power Cultivation: 47% · the engine, passive · Low」 | 〃 |
| 「Technique — The Hunter's Craft: 44% · parked, unslotted · Low」 | 〃 |
| 「Skill — The Wolf: 38% · possession · strength, speed, senses, claws · Mid」 | 〃 |
| 「Bloodline — Grey Wolf: 27% · ice · the body-line: vitality, recovery, the wolf's frame · Low」 | 〃 |
| 「Hunter's Sense: 36%」 | 〃 |
| 「Stillness: 22%」 | 〃 |
| 「Plain Speech: 29%」 | 〃 |
| 「Mountain Stride: 31%」 | 〃 |
| 「The Tally: 35%」 | 〃 |
| 「Spear: 21%」 | 〃 — five years of blisters |

## The law of this file

Every panel line that prints in a chapter must exist here, and every row
here must exist in a chapter — `tools/check_panels.py` enforces it both
ways, and a frozen or stale meter fails the build.
