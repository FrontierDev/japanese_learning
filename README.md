# Japanese Learning Dashboard

Repository-backed Japanese learning project for accelerated daily study, beginning at JLPT N5.

> **Source of truth:** the CSV files under [`data/`](data/). This README is a human-readable dashboard derived from them and should be refreshed after substantive lessons and review sessions.

<!-- DASHBOARD:START -->
## Current status

| | |
|---|---|
| **Current level** | N5 |
| **Target** | N5 completion |
| **Curriculum phase** | Phase 1 of 6 — foundations, practical movement, locations, time, dates and basic interactions |
| **Status** | Active |
| **Placement** | Complete |
| **Formal lessons completed** | 4 |
| **Last session** | 27 August 2026 |
| **Latest lesson** | [004 — Dates and Counters](lessons/n5/004-dates-and-counters.md) |
| **Latest mastery check** | Partial — date/counter material progressed; mixed retrieval exposed older particle/verb weaknesses |
| **Next lesson** | **005 — Demonstratives and Directions** |

### Next lesson

**005 — Demonstratives and Directions**

Expected focus:

- repair the `そこ / それ` distinction exposed in Lesson 004;
- consolidate `ここ / そこ / あそこ` and introduce the related demonstrative system in practical contexts;
- continue mixed retrieval of destination/existence `に` versus action-location `で`;
- reinforce `います` versus `行きます` under comprehension and production;
- use practical station/shop/direction language and appropriate location/direction kanji;
- include due date/counter retrieval without repeating the full Lesson 004 teaching load.

The lesson file should be generated from the current repository state when the session begins, rather than being pre-written far in advance.

### Current strengths

- Kana are already secure and are not part of the teaching sequence.
- Basic polite question formation with `～ですか` is reliable.
- Polite verb forms `～ます / ～ました / ～ません / ～ませんでした` are usable in practical production.
- `あります` was retrieved correctly in the Lesson 004 opening review after its previous short-term error.
- Clock time, `何時`, specific-time `に`, and `～から～まで` remain usable from Lesson 003.
- Calendar month readings such as `三月・七月・十一月` were learned quickly.
- Practical date sentences with date + `に` can now be produced, including sentences with both time/date `に` and destination `に`.
- People-counter readings `一人・二人・三人・何人` and general counters `一つ・二つ・三つ` were recalled well after instruction.
- Practical counter sentences such as `水を二つください` and `ホテルに友達が三人います` were produced correctly.

### Needs reinforcement

- **Destination/existence `に` versus action-location `で` remains the main active weakness.** Lesson 004 produced both `ホテルで何人いますか` and `店に二つ買います` under mixed retrieval.
- Keep **`います` versus `行きます`** active; one Lesson 004 comprehension item interpreted an existence sentence as movement.
- Review **`そこ` versus `それ`**; `それに猫がいます` was produced when `そこに猫がいます` was required.
- Date readings need short-term retrieval, especially **`十六日（じゅうろくにち）`** and irregular **`二十日（はつか）`**.
- People-counter word order and unnecessary `が` after a bare counter were unstable in harder sentences.
- **`九時`** was misidentified as seven o'clock in the Lesson 004 opening review.
- **`仕事`** remains unrecalled; `店` improved after being supplied and reused during the lesson.
- Continue converting familiar words such as `電車`, `明日`, `昨日`, `買います`, and `行きます` into increasingly secure kanji recognition.

### Review horizon

Immediate/near-term review is driven by the `next_review` fields in the catalogues. Current priorities include:

- `に / で` in mixed action, destination and existence sentences;
- `います / 行きます` comprehension and production;
- `そこ` and the contrast with `それ`;
- `九時`, `十六日`, `二十日`, and recently activated date kanji/readings;
- `一人 / 二人 / 三人 / 何人` in natural sentence order;
- `仕事`, with `店` checked again after its successful later reuse;
- `予約は何月何日ですか` and the contrast between `予約は十一月二十日です` and `十一月二十日に行きます`.

### Recent lessons

| Lesson | Focus | Result |
|---|---|---|
| [000](lessons/n5/000-placement.md) | N5 placement diagnostic | Placement complete; weak areas identified |
| [001](lessons/n5/001-particles-and-basic-actions.md) | Core particles and polite verb forms | 4/4 final check |
| [002](lessons/n5/002-locations-and-existence.md) | `あります / います`, location and action particles | 5/5 final check |
| [003](lessons/n5/003-times-and-schedules.md) | Time, `何時`, specific-time `に`, `～から～まで` | 7/7 final check |
| [004](lessons/n5/004-dates-and-counters.md) | Calendar dates, `何月何日`, people and general counters | Partial mixed mastery; new material progressed, older contrasts remain due |
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
