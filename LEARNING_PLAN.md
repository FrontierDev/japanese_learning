# Accelerated Japanese Learning Plan

## Starting point

The learner already reads hiragana and katakana and has some prior grammar knowledge. Kana drills are therefore excluded except where a spelling or pronunciation point specifically requires them.

The first target is practical JLPT N5 competence. Progress is mastery-based rather than strictly calendar-based: known material is tested and compressed; weak material is revisited more often.

## Daily lesson model

A normal lesson should take roughly 25–45 minutes and contain:

1. **Retrieval review** — due phrases, grammar, vocabulary, and kanji.
2. **New grammar** — normally 1–2 points.
3. **New kanji** — normally 3–5 characters, taught through useful words.
4. **Useful language** — normally 8–15 phrases/vocabulary items.
5. **Comprehension** — a short realistic dialogue, message, notice, menu, timetable, directions, or similar material.
6. **Production** — translation, response, reformulation, or sentence construction.
7. **Mastery check** — short uncued test. Failed items return to review.

Accelerated pace does not mean introducing large quantities without retrieval. New material should be reduced when previous material is not being recalled reliably.

## Teaching principles

### Useful Japanese only

Examples must resemble language a learner could plausibly need to understand or say. Prefer:

- stations, trains, buses, taxis, airports
- directions and locations
- restaurants, cafés, ordering, reservations
- shops, prices, sizes, quantities, payment
- introductions and ordinary social interaction
- plans, times, schedules, invitations
- hotels and accommodation
- asking for repetition or clarification
- describing simple problems
- everyday routines and needs
- signs, notices, menus, messages, and timetables

Avoid examples whose only value is grammatical illustration, such as "My pen is red."

### Grammar

For each grammar point, teach:

- meaning
- formation
- important nuance or restriction
- when it is actually used
- contrast with nearby grammar where useful
- realistic examples
- at least one active-production exercise

Recognition alone is not mastery.

### Kanji

Do not teach kanji as isolated English keywords. Each new kanji should include:

- core meaning
- useful reading(s)
- 2–4 high-frequency words
- at least one realistic phrase or sentence
- recognition practice in actual words

The target is the common N5 kanji range, approximately 100 characters. The JLPT does not publish a single fixed official kanji list, so the curriculum should prioritise high-frequency N5-appropriate characters.

### Phrases

Useful phrases are durable learning items, not disposable examples. When an important phrase is encountered, add it to `data/phrases.csv`. If it is explained, mark it explained. If it is tested again, increment its revision count.

## Mastery states

Use these values in the CSV catalogues:

- `new` — encountered but not yet demonstrated reliably
- `learning` — understood with support but not secure
- `review` — previously learned and scheduled for retrieval
- `mastered` — reliably understood and produced on repeated occasions

A mastered item can still appear in mixed review.

## N5 curriculum

### Phase 0 — Placement and compression

Establish what is already known before beginning the sequence. Test rather than reteach:

- です / じゃないです / でした
- は, が, を, に, で, へ, と, も, の
- これ / それ / あれ and この / その / あの
- basic polite verb forms
- present/past and positive/negative forms
- い-adjectives and な-adjectives
- ある / いる
- question words
- numbers, time, dates, and common counters

Secure items should be recorded as known and folded into mixed review rather than consuming full lessons.

### Phase 1 — Navigation and basic interactions

Grammar:

- practical particle use
- demonstratives and location words
- ある / いる
- polite verb forms
- question formation
- time, dates, frequency, counters

Contexts:

- finding places
- stations and trains
- asking where something is
- arranging times
- basic purchases

Kanji emphasis: numbers, time, days, directions, basic places.

### Phase 2 — Actions, requests, permission, and movement

Grammar:

- verb groups and core conjugation patterns
- past and negative forms
- て-form
- ～てください
- ～てもいいです
- ～てはいけません
- ～ましょう / ～ませんか
- movement with に / へ / で

Contexts:

- transport
- instructions
- meeting people
- permission
- invitations and plans

Kanji emphasis: movement, transport, people, common actions.

### Phase 3 — Description, shopping, food, and comparison

Grammar:

- い-adjective and な-adjective forms
- adjective + noun
- 好き / 嫌い / 上手 / 下手
- basic comparisons
- quantities and counters
- ～から / ～まで

Contexts:

- restaurants
- shopping
- choosing between options
- prices and quantities
- describing places and objects

Kanji emphasis: food, money, size, quantity, common descriptive characters.

### Phase 4 — Ongoing actions, wants, routines, and reasons

Grammar:

- ～ています
- ～たいです
- ～に行きます / ～に来ます
- ～てから
- ～前に / ～後で
- ～ないでください
- simple reasons with ～から

Contexts:

- daily routines
- current actions
- making requests
- explaining simple reasons
- planning what happens next

Kanji emphasis: daily activities, work/study, home, weather, common verbs.

### Phase 5 — Linking information and broader expression

Grammar:

- ～たり～たりします
- ～ことができます
- introductory ～と思います where appropriate
- noun/adjective linking
- そして / それから / でも
- frequency and degree expressions

Contexts:

- describing a day or trip
- preferences
- what is possible
- short messages and notices
- simple problems and explanations

Kanji emphasis: remaining high-frequency N5 characters, especially those found in signs, schedules, and messages.

### Phase 6 — N5 integration

Focus on:

- mixed grammar without chapter cues
- rapid kanji recognition in words
- short practical readings
- listening-style dialogues represented in text when audio is unavailable
- active sentence production
- timed N5-style questions
- targeted repair of weak catalogue items

No large new grammar load should be added here unless diagnostics expose a gap.

## Revision model

Revision should be retrieval-based. Do not merely re-show the answer.

Default spacing after a successful introduction can be approximately:

- first review: 1 day
- second review: 3 days
- third review: 7 days
- fourth review: 14 days
- later reviews: increasingly spaced

Failed or hesitant items should return sooner. The assistant may adjust spacing based on performance.

## Advancement rule

Advance rapidly when the learner produces material reliably. Slow down when production remains weak even if recognition is good.

The repository state, not lesson number alone, determines what should be taught next.