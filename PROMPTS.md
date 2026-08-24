# Prompts for Using the Japanese Learning Project

These are the recommended copy-paste prompts for interacting with this project. The repository is `FrontierDev/japanese_learning`.

## 1. Start or continue today's lesson

Use this as the normal daily prompt.

```text
Begin today's Japanese lesson. Read FrontierDev/japanese_learning first, including the learning plan, current progress, learning log, catalogues, and recent lessons. Build today's lesson from my actual recorded state. Follow the accelerated N5 plan, include due revision, grammar and kanji, and use practical natural Japanese rather than artificial textbook examples. Teach interactively rather than giving me all the answers at once. At the end of the session, update the repository with what I encountered, revised, succeeded at, or struggled with.
```

## 2. First session / placement test

Use this before beginning the main lesson sequence.

```text
Run my N5 placement lesson from FrontierDev/japanese_learning. I already know hiragana and katakana and I know some Japanese grammar, so test what I can actually understand and produce rather than teaching from zero. Work through the diagnostic interactively. When it is complete, update the repository so secure material can be compressed or skipped and weak areas can be prioritised.
```

## 3. Review session only

```text
Give me a Japanese review session using FrontierDev/japanese_learning. Read the CSV catalogues and learning log, select material that is due or weak, and test me by active recall rather than simply showing the answers. Mix phrases, grammar, kanji, vocabulary, reading, and production where appropriate. Do not introduce significant new material. At the end, update revision counts, statuses, next-review dates, and the learning log.
```

## 4. Short review when I have little time

```text
Give me a 10-minute Japanese review using FrontierDev/japanese_learning. Prioritise the most overdue or weakest items. Test me interactively and update the repository afterward.
```

## 5. Explain a phrase I encountered

Replace the Japanese text at the end.

```text
Explain this Japanese phrase in the context of my current level. Break down the grammar and vocabulary only as much as needed, tell me how natural/common it is and when I would use it, and give me 2–3 genuinely useful related examples. Check FrontierDev/japanese_learning for anything I already know that helps explain it. Add the phrase to the phrase catalogue as encountered and explained, avoiding duplicates.

[PASTE JAPANESE HERE]
```

## 6. Ask how to say something naturally

```text
How would I naturally say the following in Japanese? Give me the most useful normal phrasing first, not a literal English translation. Explain any grammar that is new relative to FrontierDev/japanese_learning. If this produces a reusable phrase worth learning, add it to the phrase catalogue as encountered and explained.

[PASTE WHAT I WANT TO SAY HERE]
```

## 7. Check Japanese that I wrote

```text
Check the Japanese below against natural Japanese and my current level in FrontierDev/japanese_learning. Tell me whether it is correct, understandable but unnatural, or incorrect. Give the smallest useful correction and explain why. Do not replace valid Japanese merely because you prefer another style. Record genuinely useful new grammar or phrases that arise from the correction.

[PASTE MY JAPANESE HERE]
```

## 8. Grammar lesson on a specific point

```text
Teach me the following Japanese grammar point. First check FrontierDev/japanese_learning so you know what related grammar I already know. Explain meaning, formation, nuance, and realistic usage concisely, then test me with practical examples and active production. Avoid Duolingo-style filler sentences. Record the grammar point and my performance in the repository.

[GRAMMAR POINT]
```

## 9. Kanji study

```text
Give me a kanji session based on FrontierDev/japanese_learning. Review due kanji first, then introduce an appropriate number of new N5 kanji for my current pace. Teach them through useful words and phrases, not isolated English keywords, and only require readings that are useful at this stage. Test recognition and production where sensible, then update the kanji, vocabulary, and learning-log CSV files.
```

## 10. Explain Japanese from an image, sign, menu, game, or website

```text
Explain the Japanese in this material for me at my current level. Use FrontierDev/japanese_learning to distinguish grammar/kanji I already know from genuinely new material. Focus on what the Japanese actually means in context and how it is used. Add useful reusable phrases, vocabulary, grammar, or kanji that I choose to learn to the repository, but do not catalogue every incidental word automatically.
```

Then attach the image or provide the text.

## 11. Conversation practice

```text
Run a practical Japanese conversation with me based on my current level in FrontierDev/japanese_learning. Pick a realistic situation and speak mostly in Japanese, but do not use large amounts of grammar or kanji far beyond my recorded level without support. Let me respond before continuing. Correct important mistakes without interrupting every minor issue. At the end, briefly review my recurring problems and update relevant revision data in the repository.
```

## 12. Reading practice

```text
Give me a short practical Japanese reading exercise appropriate to my current level in FrontierDev/japanese_learning, such as a message, notice, timetable, menu, directions, or short dialogue. Do not pre-translate it. Ask comprehension questions first, then explain only what I need. Record relevant review performance and useful new material afterward.
```

## 13. Check progress

```text
Read FrontierDev/japanese_learning and give me a concise progress report. Tell me what N5 material is secure, what is currently being learned, what is weak or overdue for review, how far through the curriculum I am, and what the next few lessons should focus on. Base this only on the repository data rather than guessing from chat history.
```

## 14. End a session and make sure it is saved

Use this if a session has wandered into ordinary conversation and you want to force a writeback.

```text
End this Japanese study session. Summarise what I actually learned or revised in this conversation, then write the appropriate changes to FrontierDev/japanese_learning: catalogue updates, revision counts, statuses, next-review dates, one learning-log row, and progress if necessary. Do not mark something mastered merely because it was explained to me. Confirm exactly which repository files were changed.
```

## 15. Resume after time away

```text
I am returning to Japanese study after a break. Read FrontierDev/japanese_learning, determine how long it has been since my last recorded session and what material is most in need of retrieval, then run a recovery review before introducing new material. Update the repository when we finish.
```

## Minimal everyday prompts

Once the project is established, these shorter prompts are acceptable because `ASSISTANT_INSTRUCTIONS.md` defines the workflow:

```text
Today's lesson.
```

```text
Review me.
```

```text
Explain: [JAPANESE]
```

```text
How do I naturally say: [ENGLISH]
```

```text
Check this: [MY JAPANESE]
```

For important sessions, prefer the full prompts above because they explicitly require repository read/write behaviour.