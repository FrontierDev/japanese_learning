# Lesson 000 — N5 Placement and Compression

**Purpose:** determine which elementary material can be compressed and which areas need active teaching.

## Tutor instructions

- Administer this interactively in small groups of questions. Do not dump the whole test at once.
- Do not show model answers before the learner answers.
- Accept natural equivalent Japanese, not only the suggested model answer.
- Separate grammar problems from vocabulary gaps where possible.
- A correct guess or multiple-choice recognition is weaker evidence than free production.
- Record secure, partial, and weak domains after the diagnostic.

## Part A — Practical comprehension

Ask the learner what each sentence means. Exact English wording is not required.

1. すみません、駅はどこですか。
2. この電車は新宿に行きますか。
3. 東京までいくらですか。
4. 明日は仕事がありません。
5. 昨日、友達とレストランで食べました。
6. ここで写真を撮ってもいいですか。
7. 今、ホテルの前で待っています。
8. 水を二つください。

### Diagnostic targets

- question formation
- は / に / まで / と / で / を
- present/past verb comprehension
- negative forms
- ある
- て-form-derived structures
- counters/quantity

## Part B — Particles in context

Ask the learner to fill each blank and explain the meaning of the resulting sentence.

1. 七時___ホテル___出ます。
2. 駅までバス___行きます。
3. コンビニ___水___買いました。
4. 明日、友達___京都___行きます。
5. テーブルの上___鍵があります。
6. 田中さん___日本語___話しました。

Possible natural answers depend on interpretation; discuss alternatives rather than treating every blank as mechanically unique.

## Part C — Active production

Ask the learner to say these naturally in Japanese. Do not demand literal word-for-word translations.

1. Where is the station?
2. What time is the next train?
3. I went to Kyoto yesterday.
4. Is there a convenience store near here?
5. Please say that again.
6. I want to eat Japanese food tonight.
7. Can I pay by card?
8. Let's meet in front of the station at seven.

### What to observe

- question words
- particles
- tense
- ある / いる
- requests
- ～たい
- permission/possibility strategies
- invitation/planning language

Do not penalise the learner for not yet knowing a structure that is beyond what has been taught; use the attempt to place it in the curriculum.

## Part D — Adjectives and basic forms

Prompt the learner to transform or complete the ideas naturally.

1. この店は高いです。→ make it past.
2. このホテルは静かです。→ make it negative.
3. この電車は速いです。→ ask whether it is fast.
4. 昨日は忙しいです。→ correct the tense.
5. 京都はきれいです。→ make it past negative if known.

Diagnostic targets:

- い-adjective inflection
- な-adjective/copula patterns
- question formation

## Part E — Kanji recognition in useful words

Ask for the reading or meaning of the whole word/phrase where possible. Do not require isolated readings if the learner recognises the word.

1. 日本
2. 三時
3. 七月
4. 一人
5. 大きい
6. 小さい
7. 上
8. 下
9. 出口
10. 電車

Record individual kanji that are clearly secure, uncertain, or unknown. Recognition in vocabulary counts more than memorising an English keyword.

## Part F — Short practical reading

Present this without translation:

> 田中さんへ  
> 明日の昼、駅の前で会いませんか。十二時はどうですか。  
> 私は十一時半まで仕事です。駅まで電車で十五分ぐらいです。  
> — 山田

Ask:

1. What is Yamada proposing?
2. Where do they plan to meet?
3. What time is suggested?
4. Why is the timing relevant?
5. Roughly how long does Yamada need to reach the station?

Then ask the learner to write or say a short reply accepting or changing the plan.

## Placement outcome

Classify each domain as `secure`, `partial`, or `weak`:

- copula and basic noun sentences
- core particles
- question words
- polite verb present/past
- negative forms
- adjectives
- ある / いる
- counters/time
- て-form familiarity
- requests/permission
- wants/plans
- basic kanji recognition
- short practical reading
- active sentence production

## Writeback after completion

1. Add demonstrated grammar to `data/grammar.csv` with an appropriate state. Secure prior knowledge may begin as `review`; do not mark it `mastered` from one diagnostic response alone.
2. Add clearly known/unknown diagnostic kanji as appropriate to `data/kanji.csv`.
3. Add useful phrases the learner encountered and wants retained to `data/phrases.csv`.
4. Append the placement session to `data/learning_log.csv`.
5. Change `data/progress.csv` from `placement_pending` to the appropriate starting phase and next lesson.
6. Create `lessons/n5/001-*.md` based on the actual gaps rather than blindly following a fixed sequence.