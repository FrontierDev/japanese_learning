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
| **Last session** | 19 September 2026 |
| **Latest lesson** | [005 — Demonstratives and Directions](lessons/n5/005-demonstratives-and-directions.md) |
| **Latest review** | [Re-entry review — 19 September 2026](lessons/n5/review-2026-09-19-reentry.md) |
| **Latest result** | Review/re-entry after an 18-day gap — substantial initial rust, followed by strong recovery; two immediate repair items remain |
| **Next lesson** | **006 — Frequency and Weekdays** |

### Next lesson

**006 — Frequency and Weekdays**

Before introducing new material, begin with a short uncued re-entry check:

- `九時（くじ）`;
- `二十日（はつか）`;
- `何人（なんにん）`;
- `そこに何がありますか`;
- one `何時に` question;
- one `～から～まで` schedule sentence.

If these are retained, continue into the planned Lesson 006 material:

- practical frequency language;
- weekdays and ordinary schedules/opening days;
- useful schedule/frequency vocabulary;
- an appropriate 3–5-kanji batch through useful words;
- a realistic timetable/message-style comprehension task;
- active production mixed with older Phase 1 grammar.

If the opening repair items have decayed again, use another short review block rather than forcing new material.

### Current strengths

- Kana remain secure.
- Core destination/existence `に` versus action-location `で` recovered well; the learner accurately explained the distinction and repeatedly used `で` correctly in shopping/eating sentences.
- Past tense recovered after one opening lapse: later `買いました` and `食べました` were correct.
- General and people counters recovered well in production: `水を三つ`, `水を二つ`, `友達が二人います`, and `友達が三人います`.
- Relative-location grammar remains usable: `駅の右にコンビニがあります` and `テーブルの上に水があります` were recovered.
- `建物（たてもの）`, `下（した）`, and `仕事（しごと）` were initially weak after the gap but were retrieved correctly later in the session.
- `九時（くじ）` and `二十日（はつか）` were eventually retrieved correctly after repeated repair.

### Needs reinforcement

- **`何人` reading is immediate priority:** the final isolated reading was `なんじん`; target is **`なんにん`**.
- **Existence-question frame needs one more check:** `そこに何ありますか` correctly selected `そこ` and `あります` but omitted **`が`**; target is `そこに何がありますか`.
- **`九時（くじ）` remains short-interval review:** it required multiple attempts before successful retrieval.
- **`二十日（はつか）` remains short-interval review:** `はつにち` appeared twice before the correct irregular reading returned.
- `何時に` and `～から～まで` were repaired successfully, but both were malformed on the first final-review attempt after the study gap.
- `それ` versus standalone `この` recovered, but exact sentence particles still need attention: one attempt omitted `は`.
- `上 / 下` were recoverable but each was briefly forgotten in production.
- Continue spaced recognition of familiar kanji-bearing words rather than assuming long-gap retention.

### Review horizon

Current priorities derived from the 19 September review:

- **immediate:** `何人（なんにん）`, `九時（くじ）`, `二十日（はつか）`, and `そこに何がありますか`;
- **short review:** `何時に行きますか`, `予約は何月何日ですか`, `～から～まで`, `上 / 下`, `そこ / それ`, and `あります / います`;
- **short-to-medium spacing:** `三つ / 二つ`, `建物`, `仕事`, past `～ました`, and mixed counter order;
- **longer spacing after successful retrieval:** action-location `で`, `駅の右`, `近くにコンビニがありますか`, and `二人 / 三人` production.

### Recent lessons / sessions

| Session | Focus | Result |
|---|---|---|
| [000](lessons/n5/000-placement.md) | N5 placement diagnostic | Placement complete; weak areas identified |
| [001](lessons/n5/001-particles-and-basic-actions.md) | Core particles and polite verb forms | 4/4 final check |
| [002](lessons/n5/002-locations-and-existence.md) | `あります / います`, location and action particles | 5/5 final check |
| [003](lessons/n5/003-times-and-schedules.md) | Time, `何時`, specific-time `に`, `～から～まで` | 7/7 final check |
| [004](lessons/n5/004-dates-and-counters.md) | Calendar dates, `何月何日`, people and general counters | Partial; new material progressed but older contrasts remained due |
| [005](lessons/n5/005-demonstratives-and-directions.md) | Demonstratives, relative locations, direction kanji | Partial; strong demonstrative/direction progress, reading/counter repair remained due |
| [Review 19 Sep](lessons/n5/review-2026-09-19-reentry.md) | Re-entry after 18-day gap | Strong recovery after repeated retrieval; `何人` reading and existence-question `が` remain immediate repair items |
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
