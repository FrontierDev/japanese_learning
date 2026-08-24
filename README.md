# Japanese Learning

Repository-backed Japanese learning project for accelerated daily study, beginning at JLPT N5.

## Objectives

- Reach practical N5 competence before progressing to higher levels.
- Cover grammar, kanji, vocabulary, reading, comprehension, and active production.
- Assume hiragana and katakana are already known.
- Compress or skip elementary material that is already secure.
- Use realistic Japanese rather than artificial textbook sentences.
- Retain durable learning state in compact CSV files.

## Repository structure

```text
japanese_learning/
├── README.md
├── LEARNING_PLAN.md
├── ASSISTANT_INSTRUCTIONS.md
├── PROMPTS.md
├── data/
│   ├── progress.csv
│   ├── learning_log.csv
│   ├── phrases.csv
│   ├── grammar.csv
│   ├── kanji.csv
│   └── vocabulary.csv
├── lessons/
│   └── n5/
│       └── 000-placement.md
└── templates/
    ├── daily_lesson.md
    └── review_lesson.md
```

## How to use this project

1. Connect ChatGPT to this repository.
2. Use the prompts in `PROMPTS.md`.
3. The assistant reads the current curriculum and CSV state before teaching.
4. New lessons are stored under `lessons/`.
5. Encountered material and revision counts are written back to `data/` after study.

The repository is the source of truth for what has been introduced, revised, and mastered.