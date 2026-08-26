# Japanese Learning Dashboard

Repository-backed Japanese learning project for accelerated daily study, beginning at JLPT N5.

> **Source of truth:** the CSV files under [`data/`](data/). This README is a human-readable dashboard derived from them and should be refreshed after substantive lessons and review sessions.

<!-- DASHBOARD:START -->
## Current status

| | |
|---|---|
| **Current level** | N5 |
| **Target** | N5 completion |
| **Curriculum phase** | Phase 1 of 6 — foundations, practical movement, locations, time and schedules |
| **Status** | Active |
| **Placement** | Complete |
| **Formal lessons completed** | 3 |
| **Last session** | 26 August 2026 |
| **Latest lesson** | [003 — Times and Schedules](lessons/n5/003-times-and-schedules.md) |
| **Latest mastery check** | 7/7 |
| **Next lesson** | **004 — Dates and Counters** |

### Next lesson

**004 — Dates and Counters**

Expected focus:

- practical dates and calendar expressions;
- counters needed at N5 level;
- continued use of time expressions and specific-time `に`;
- appropriate new kanji through useful words rather than isolated memorisation;
- retrieval of weak/due material before introducing new material.

The lesson file should be generated from the current repository state when the session begins, rather than being pre-written far in advance.

### Current strengths

- Kana are already secure and are not part of the teaching sequence.
- Basic polite question formation with `～ですか` is reliable.
- Polite verb forms `～ます / ～ました / ～ません / ～ませんでした` are usable in practical production.
- `あります / います` and the basic existence-location pattern are understood.
- Practical location sentences can be produced with `に`, `で`, `が`, and `を` after correction/retrieval.
- Clock time, `何時`, specific-time `に`, and `～から～まで` were successfully used in Lesson 003.
- Lesson 003 ended with a **7/7 uncued mastery check**.

### Needs reinforcement

- Continue mixing **action-location `で`** and **destination/existence `に`**; this distinction has improved but has produced repeated errors under retrieval.
- Review the exact form of **あります**; `がります` appeared once during retrieval.
- Keep `～じゃないです` active with な-adjectives such as `静か` so verb-negative forms are not overgeneralised.
- Continue converting familiar words such as `電車`, `明日`, `昨日`, `買います`, and `行きます` into increasingly secure kanji recognition.
- Several basic N5 kanji encountered during placement remain deliberately deferred and should be introduced gradually in useful vocabulary rather than as a bulk list.

### Review horizon

Immediate/near-term review is driven by the `next_review` fields in the catalogues. Current priorities include:

- `あります` and recently encountered clock-time kanji such as `五` and `九`;
- core polite verb forms and familiar kanji-bearing vocabulary;
- mixed `に / で` production;
- `何時に～`, `～から～まで`, and recent time kanji;
- location/existence phrasing such as `近くにコンビニがありますか`.

### Recent lessons

| Lesson | Focus | Result |
|---|---|---|
| [000](lessons/n5/000-placement.md) | N5 placement diagnostic | Placement complete; weak areas identified |
| [001](lessons/n5/001-particles-and-basic-actions.md) | Core particles and polite verb forms | 4/4 final check |
| [002](lessons/n5/002-locations-and-existence.md) | `あります / います`, location and action particles | 5/5 final check |
| [003](lessons/n5/003-times-and-schedules.md) | Time, `何時`, specific-time `に`, `～から～まで` | 7/7 final check |
<!-- DASHBOARD:END -->

## Start today's lesson

Copy and paste this as the **normal daily prompt**:

```text
Begin today's Japanese lesson. Read FrontierDev/japanese_learning first, including the learning plan, current progress, learning log, catalogues, recent lessons, and dashboard. Build today's lesson from my actual recorded state. Follow the accelerated N5 plan, include due revision, grammar and kanji, and use practical natural Japanese rather than artificial textbook examples. Teach interactively rather than giving me all the answers at once. At the end of the session, update the repository with what I encountered, revised, succeeded at, or struggled with, and refresh the README dashboard so it accurately shows my current progress and next lesson.
```

The short form **`Today's lesson.`** is also acceptable once the repository is available to the tutor, but the full prompt above is preferred when repository read/write behaviour needs to be explicit.

## Project files

- [`LEARNING_PLAN.md`](LEARNING_PLAN.md) — accelerated N5 curriculum and progression policy.
- [`ASSISTANT_INSTRUCTIONS.md`](ASSISTANT_INSTRUCTIONS.md) — authoritative tutor behaviour and repository writeback rules.
- [`PROMPTS.md`](PROMPTS.md) — copy-paste prompts for lessons, review, grammar, kanji, conversation, corrections, and progress checks.
- [`data/progress.csv`](data/progress.csv) — compact current position and next lesson.
- [`data/learning_log.csv`](data/learning_log.csv) — one compact record per substantive study session.
- [`data/phrases.csv`](data/phrases.csv) — encountered/revised reusable phrases.
- [`data/grammar.csv`](data/grammar.csv) — grammar state and revision schedule.
- [`data/kanji.csv`](data/kanji.csv) — kanji state, useful readings, words, and revision schedule.
- [`data/vocabulary.csv`](data/vocabulary.csv) — vocabulary state and revision schedule.
- [`lessons/n5/`](lessons/n5/) — completed/generated N5 lesson material.
- [`templates/`](templates/) — daily and review lesson templates.

## Design principles

- Accelerated progression: test and compress material already understood.
- Practical Japanese: transport, travel, restaurants, shops, directions, schedules, accommodation, social interaction, notices, and everyday needs.
- Active production rather than recognition-only exercises.
- Grammar taught with enough explanation to understand *why* it works before testing it.
- Kanji taught through useful vocabulary and context, not isolated English keywords.
- Durable learning state remains compact in CSV; this README is a convenient derived view, not an additional competing source of truth.
