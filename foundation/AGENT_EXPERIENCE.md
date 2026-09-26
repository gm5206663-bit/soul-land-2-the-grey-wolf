# Agent Experience — Soul Land 2: The Grey Wolf

Date: 2026-09-26
Project: Soul Land 2 fanfic — OC Ye Cang, grown Earth man reborn, silent wolf, innate 1 beside Huo Yuhao
Progress: F0-F22, 6 chapters, 80 panel rows, 10 releases, 79 self-audit checks PASS

Purpose: Share everything learned so other agents can work faster and avoid same strikes.

---

## 1. How User Teaches — Serial Locks

User teaches by strike, not by long spec. Each lock = one correction you must keep forever.

- **F0** OC premise: grown Earth, full meta knowledge of Soul Land, silent, wolf martial soul, innate 1 start. Innate is start, not ceiling.
- **F2** Bloodline at awakening: Grey Wolf 7% Low on night one. Bloodline gives body, senses, recovery, appearance.
- **F3** Research everything: web_search canon before writing. Wolf souls mostly ice. Stormwind = wind. Ghost Wolf = patient hunter.
- **F4** All foundation files must exist: SYSTEM_SPEC, STATUS, METERS, PANELS, SKILLS_CANON, FOUNDATION, RULINGS_LOG, TIMELINE, STORY_ARCS, etc.
- **F5** Workshop refresh: workspace can wipe. Keep backup clone at /tmp/mine/wolf. Use tar, not rsync. Restore .git via cp -r.
- **F6** "Do yourself": agent must rebuild foundations, not ask user.
- **F7** FULL panels: full panel at every gate (night one, rank up, year end). Every other beat panel short. Drift guard checks that every 「...」 in chapters exists in PANELS.md and reverse. Must stay IN SYNC.
- **F8** Honest pace: level 10 wall held 3 years. Pour 12 to 29 is 17 levels in one year. No inflated growth.
- **F9** Grade ladder: Waste / Ordinary / Excellent / Top-tier / Divine for martial souls. Low / Mid / High / Top / Ultimate for current readings. Rings white > yellow > purple > black > red.
- **F10** Ring seats bloodline: each ring seats its beast bloodline. Ghost 1% Low, Stormwind 15% Mid.
- **F11** Full grant: each ring gives 7 things — SKILL, RANK GIFT, SOUL UPGRADE, BODY FLOOD, BLOOD, YEARS, TITLE. Years: white 10, yellow 100, purple 1000, black 10000, red 100000. First ring limit ~420y but ages after seating.
- **F12** Walls: bottlenecks at 10,20,30. No ring = no crossing.
- **F13** Honest yield 24/7: slotted techniques run at best 24/7 even while sleeping. Hours that count are hours engine runs. Two slots for 5 years = decades of part-time.
- **F14** Mastery: basic methods have no numbered stages. At 100% they become 100% MASTERED with grade Low>Mid>High. Pool quality deepens. Aging is pour-based, not calendar. Ghost 120y to 168y via levels + hours, not months.
- **F15** Interconnection: effective talent = innate 1 + Grey + Ghost + Stormwind + basics + fusion. At Ch5 ~3.5x. Appearance changes with bloodline: frame, height, amber eyes, grey tint hair, dogs ignore him.
- **F16** Thousand-year gate: by Ch5, Ghost 1350y purple, Stormwind 1850y purple, Level 29-30, everything Mid+, Grey Ridge Hunt fusion of basics.
- **F17** Evolution: Grey Wolf > Ice Wolf > Frost Ghost Wolf > Storm Frost Ghost Wolf when Grey 65% High + both rings purple. Skill upgrade on color break: Netherlight > Ghost Veil, Windstride > Storm Step. Ring Veil hides purple as yellow. Fool shows two thousand-year rings.
- **F18** Full status strike: user said "what level they are not mastered" and "where wind attribute even" and "how strong body". Fix: all 15 life-skills 100% MASTERED High, martial soul ice+wind, body ~500kg lift robust, named technique like Purple Demon Eyes 4 stages, Spirit Sea 850, wind attribute even, STATUS.md must have everything not just system panel.
- **F19** Skills like canon: rewrite skills with canon format — Name, Ring, Type, Activation, Appearance, Effect, Duration, Range, Cost, Origin Beast, Evolution. Check Dai Mubai White Tiger possession and Feng Xiaotian Wind Blade Burst as anchors.
- **F20** Ghost Wolf canon: golden lock on forehead at 1000y, iron-gray coat, green eyes, toughest skull, fragile body, tofu waist (waist/neck weak), Light of Netherworld speed aura, Ghost Doppelganger 3 clones, Shrek Beast Dueling Area vs Huo Yuhao + He Caitou, skull shattered by Dark Gold Terror Claw Bear.
- **F21** Correct everything: self-audit 79 checks, run_all green, panels 80 IN SYNC.
- **F22** Road craft: Ch6 The Hem Road, no fight, show Grey Ridge Hunt in daily life — control, body control, five senses, stillness, observation. User rule: "Not every time, in chapter you only write when there is update or just gain, then you write full, normally I can check in status file". So Ch6 has 0 panel lines.

Keep all locks forever unless user reverses.

---

## 2. Standing Rules

- Re-export git identity every bash: GIT_AUTHOR_NAME, GIT_AUTHOR_EMAIL, GIT_COMMITTER_NAME, GIT_COMMITTER_EMAIL. Bash does not preserve env.
- No gh CLI. Use REST API with PAT for releases.
- Use tar for backup, not rsync.
- Avoid "the-way" phrase. Style gate fails on it.
- Avoid sentences over 60 words. Split long sentences.
- Stop writing chapters until foundations approved.
- Ask via ask_user when ambiguous.
- Check canon perfectly before writing.

---

## 3. Workspace Management

- Snapshot saves only /home/user. Excludes .arena, .cache, node_modules, dist, build, .git/config etc. Cap ~128MB / 10k files.
- Bash cwd resets each call. Always cd to project.
- Keep backup: `tar -cf /tmp/mine/wolf.tar -C /home/user soul-land-2-the-grey-wolf --exclude=.git --exclude=docs --exclude=manuscript`
- Restore .git: `cp -r /tmp/mine/wolf/.git ./`
- /tmp wipes on restart. Keep clone at /tmp/mine/wolf.

---

## 4. GitHub Management

- Remote: origin main. Current HEAD ahead after push.
- Before commit: `python3 tools/run_all.py` must be green. Then `python3 tools/check_panels.py` must be IN SYNC.
- Docs: `docs/` has 6 chapters + index.html built by run_all.
- Manuscript: `manuscript/` has 6 reader editions + FULL.
- Releases: 10 releases v0.6.3-f16 to v0.6.9-f22 via REST. Each has one zip asset. POST /repos/OWNER/REPO/releases then POST /uploads/.../assets.
- Files to update each push: README.md, CHANGELOG.md, NEXT.md, docs/, manuscript/ if changed, foundation/ if changed.

---

## 5. Canon Checking Method

- Use web_search depth 3 for spiritual realms, Purple Demon Eyes, body thousand-year, Stormwind attribute.
- Use fetch_page for fandom wiki, may need chunkIndex.
- Keep receipts in docs or memory.
- Key facts learned:
  - Spiritual realms: Spirit Origin 0-99, Connection 100-499, Sea 500-4999, Abyss 5k-19k, Domain 20k-49k, Divine Origin 50k+, God King. Current 850 = Spirit Sea.
  - Purple Demon Eyes: 4 stages Survey/Attention/Intoxication/Immersion, training purple qi morning, effects vision + confuse/stun + mind's eye 10-100m.
  - Body thousand-year: 10y ring +10, 100y +100, 1000y +1000. Pool deepened, pathways widened, vitality. Beast bodies robust even without release.
  - Stormwind Demon Wolf: Wind attribute, Wind Blade Burst 10 half crescent, Wings 50m flight, Wolftaken, rank 20-30.
  - Ghost Wolf thousand-year: golden lock, iron-gray, green eyes, toughest skull, tofu waist, Light of Netherworld, 3 clones, Shrek duel vs Yuhao + Caitou, Dark Gold Terror Claw Bear shatters skull.
  - Beast possession format: grey light surges, bones cracking, muscles expand, hair dyed, claws 20cm, pupils dark blue, etc.

Always cite with [id](url) when using search results.

---

## 6. Panel Ledger Drift Guard

- Tools: `tools/check_panels.py` enforces both directions.
- Every 「...」 line in chapters must exist in PANELS.md.
- Every row in PANELS.md must appear in chapters or be marked retired.
- Current: 80 rows — Ch1 12, Ch2 14, Ch3 14, Ch4 18, Ch5 22, Ch6 0. IN SYNC.
- Bare panels not allowed: must have grade or description.
- When adding panel, update both chapter and PANELS.md same turn.

---

## 7. Style Gate

- Tool: `tools/run_all.py` runs manuscript sync + style gate + site + panel check.
- Checks:
  - Word count band: 2400-3400 per chapter. Ch6 2677w IN.
  - Avg sentence length, median, max.
  - Dialogue density per 1000w.
  - over60 must be 0. Fix by splitting into short sentences.
  - the-way must be 0. Fix by removing phrase.
  - bare must be 0.
- If FAIL, fix first, then commit.

---

## 8. Status File — Full Status Completely Everything

User wants full status in STATUS.md, not just system panel.

Must include:
- Basic Info: Name Ye Cang, Age 11, Level 30 Great Soul Master, Martial Soul Storm Frost Ghost Wolf ice+wind High, Slots 3/3/3
- Body: ~500kg lift, robust beast-type, denser bone, quicker muscle, predator frame, amber ice-amber eyes, grey tint hair, height shoulders, cold tolerance, recovery, appearance freight, dogs ignore, wood passes at peace
- Spiritual Realm: Spirit Sea 850, vast as sea, perception 10-100m, house fly detail
- Soul Power: dense dark pure, all-hours circulation at mastery, three bloodlines feeding
- Techniques: Basic Cultivation 100% MASTERED High, Hunter's Craft 100% MASTERED High, Grey Ridge Hunt 100% MASTERED High + Ring Veil
- Life-skills: all 15 100% MASTERED High — Sense, Stillness, Speech, Stride, Tally, Spear, Soul Power Control, Observation, Body Control, Five Senses, Reading, Understanding, Basic Spearmanship, Cooking, Combat Style
- Rings: Ghost 1350y purple (concealed 120y yellow), Stormwind 1850y purple (concealed 603y yellow)
- Skills canon format: Possession, Ghost Veil, Storm Step with full appearance and effects and future possibilities
- Bloodlines: Grey 65% High ice +1.30 true ice, Ghost 35% Mid +0.35 quiet step, Stormwind 15% Mid +0.225 wind
- Named Techniques: Grey Ridge Hunt 4 stages Perception/Attention/Intoxication/Immersion like Purple Demon Eyes, training purple qi morning, effects mind's eye Wide-Area
- Attributes, Grades, Body Strength full sections
- Future: True Body 70+, Domain, Soul Bone, Core, Ring ageing black/red, Divine Beast evolution, Fusion Skill

---

## 9. Life-Skills, Body, Spirit Sea, Wind Attribute

- All basics 100% MASTERED High — user strike "he doesn't master all basic things"
- Body ~500kg robust — 2 thousand-year rings give 2000 attribute increase + Grey body-line
- Spirit Sea 850 — perception 10-100m, battleship pilot foundation
- Wind attribute even — Stormwind bloodline gives wind, martial soul ice+wind mutation allowed by canon (Beast soul may mutate)
- Named technique like Purple Demon Eyes: Grey Ridge Hunt 4 stages, own training, own effects, incantation "hunt."

---

## 10. Skills Description Like Soul Land Canon

Format:
- Name / Ring / Type / Activation / Appearance / Effect / Duration / Range / Cost / Origin Beast / Evolution / Canon Anchor
- Example: Dai Mubai White Tiger Protective Barrier — pale white light, muscles expand, golden hair, king pattern, hands double size, white fur, claws 20cm, defense +50%
- Example: Feng Xiaotian Wind Blade Burst — 10 half crescent sealing evasion, Double Wolf Possession +50%, Wings flight 50m, Tornado, 36 Continuous Slashes increasing each chop

Ye Cang:
- Possession: grey light surges, bones cracking, muscles expand, stature larger, hair grey frost tint, amber ice-amber eyes, claws, grey fur, cold air + wind curls, strength +100%, speed +80%, senses +200%, defense +60%
- Ghost Veil: Light of Netherworld speed boost + mitigation + 3 clones + toughest skull + tofu waist + invisibility 2s + confuse/stun
- Storm Step: Wind Blade Burst 10 half crescent 20m + Wings 50m 15s + afterimage 2-3 + future Tornado + 36 Slashes

Many things possible future: self-created skills, True Body giant 5m+ ice+wind domain 100-300%, Domain Grey Ridge Domain, Soul Bone Ghost Leg + Wing Bone, Blood Essence Core / Soul Core, Ring ageing black 10k red 100k, Further Evolution Extreme Ice -150C Extreme Wind, Fusion Skill with Yuhao, Tang Sect Methods.

---

## 11. Chapter Rule

User rule: "Not every time, in chapter you only write when there is update or just gain, then you write full, normally I can check in status file everything when needed"

- At gate (absorption, level up, evolution) → write full panel
- No update → 0 panel lines allowed, keep prose short, show skills in daily life
- Ch6 = 0 lines, allowed, ledger still IN SYNC

---

## 12. Helpful Tips For Other Agents

- Always ask questions first via ask_user before big changes.
- Keep foundations approved before chapters.
- Run run_all + check_panels before every commit.
- Split long sentences to avoid over60.
- Avoid "the way" phrase.
- Bloodline is not joke — gives many things: vitality, recovery, frame, senses, ice, wind, appearance, talent, martial soul growth.
- Aging is pour-based, not calendar — levels + engine hours + bloodlines age rings.
- Skill upgrade on color break — keep identity, grow power.
- Concealment is smart — hide purple as yellow via Ring Veil.
- Evolution needs High + purple + bloodlines — strange change awakening.
- Keep effective talent growing — innate is start.
- Keep appearance consistent — frame freight, amber eyes, grey tint, dogs no lift, wood passes at peace.

---

All lessons shared clean and clear. Other agents can learn and build.
