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
| **Formal lessons completed** | 5 |
| **Last session** | 1 September 2026 |
| **Latest lesson** | [005 — Demonstratives and Directions](lessons/n5/005-demonstratives-and-directions.md) |
| **Latest mastery check** | Partial — 4 fully correct, 2 partial, 1 incomplete; demonstratives/directions progressed strongly while a few reading/counter items remain due |
| **Next lesson** | **006 — Frequency and Weekdays** |

### Next lesson

**006 — Frequency and Weekdays**

Expected focus:

- immediately retrieve `九時（くじ）`, `二十日（はつか）`, `三つ`, and the spelling `テーブル` before showing answers;
- briefly re-test `そこ / それ`, `この / その / あの`, and relative locations such as `駅の右 / ホテルの左` without reteaching them if retrieval remains secure;
- continue mixed destination/existence `に` versus action-location `で`, now as background integration rather than the entire lesson focus;
- introduce practical N5 frequency language and weekday/schedule language in contexts such as opening days, travel plans, work and ordinary routines;
- add an appropriate 3–5-kanji batch through useful schedule/frequency words rather than isolated character drilling;
- retain active production and a realistic timetable/message-style comprehension task.

The lesson file should be generated from the current repository state when the session begins, rather than being pre-written far in advance.

### Current strengths

- Kana are secure and remain outside the teaching sequence.
- Basic polite question formation with `～ですか` is reliable.
- Polite verb forms are broadly usable; Lesson 005 repaired an opening past-tense lapse and ended with correct `買いました`.
- `あります / います` became substantially more stable in Lesson 005, especially in repeated direction/location sentences.
- Existence-location `に` and action-location `で` improved markedly after opening repair; final shopping production correctly used `店で`.
- The `そこ / それ` distinction was repaired during Lesson 005, and the broader `ここ / そこ / あそこ`, `これ / それ / あれ`, and `この / その / あの + noun` systems are now usable with short review.
- Relative-location expressions with `上・下・前・左・右` were learned quickly and used successfully in practical station/hotel/table contexts.
- People-counter order improved from early `二人友達` / `友達三人が` errors to reliable `友達が二人います` by the final check.
- `静かな + noun` was successfully applied after one correction, including `駅の右に静かなホテルがあります`.

### Needs reinforcement

- **`九時（くじ）` remains an immediate reading weakness.** The meaning “nine o'clock” is now known, but the final check still used `きゅう…` rather than `くじ`.
- **`二十日（はつか）` remains an immediate irregular-date weakness.** The learner knows it means the 20th but did not retrieve the special reading in Lesson 005.
- **`～つ` quantity retrieval needs another mixed check.** `三つ` was omitted from the final “bought three waters” sentence even though the rest of the sentence was correct.
- **`テーブル` spelling needs short review;** `ターブル` recurred several times while the surrounding grammar was correct.
- Keep `に / で` mixed into future production. The distinction improved, but the Lesson 005 opening still reproduced the older action-location `に` error.
- `あれ` and `建物（たてもの）` were introduced but not independently retrieved.
- `仕事（しごと）`, `何人`, and several older catalogue items remain overdue because they were not directly tested in Lesson 005.
- Continue converting familiar kanji-bearing words such as `電車`, `明日`, `昨日`, `買います`, and `行きます` into increasingly automatic recognition.

### Review horizon

Immediate/near-term review is driven by the catalogue `next_review` fields. Current priorities include:

- immediate: `九時（くじ）`, `二十日（はつか）`, `三つ`, `テーブル`, and `近く`;
- first retrieval: `あれ` and `建物（たてもの）`;
- short review: `そこ / それ`, `この / その / あの`, `上 / 下`, and natural `友達が二人います` counter order;
- mixed review: existence-location `に`, action-location `で`, `あります / います`, and past `～ました`;
- overdue older items not reached in Lesson 005: `仕事`, `何人`, `予約は何月何日ですか`, and `ホテルに友達が何人いますか`;
- continue spaced retrieval of `前 / 左 / 右` and useful direction phrases rather than repeating the full teaching sequence.

### Recent lessons

| Lesson | Focus | Result |
|---|---|---|
| [000](lessons/n5/000-placement.md) | N5 placement diagnostic | Placement complete; weak areas identified |
| [001](lessons/n5/001-particles-and-basic-actions.md) | Core particles and polite verb forms | 4/4 final check |
| [002](lessons/n5/002-locations-and-existence.md) | `あります / います`, location and action particles | 5/5 final check |
| [003](lessons/n5/003-times-and-schedules.md) | Time, `何時`, specific-time `に`, `～から～まで` | 7/7 final check |
| [004](lessons/n5/004-dates-and-counters.md) | Calendar dates, `何月何日`, people and general counters | Partial; new material progressed but older contrasts remained due |
| [005](lessons/n5/005-demonstratives-and-directions.md) | Demonstratives, relative locations, direction kanji | Partial; strong demonstrative/direction progress, immediate reading/counter repair still due |
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
