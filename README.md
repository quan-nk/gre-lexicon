# GRE Lexicon

**Live site:** https://quan-nk.github.io/gre-lexicon/

A small, self-contained study app I built to prepare for GRE Verbal around a full-time job. It has three parts:

- **Words:** 300 advanced GRE words with US pronunciation, plain-English meanings, example sentences and a mixed recall test.
- **Essays:** 200 model "Analyze an Issue" essays at the 6 level, each with an analysis of why it earns a 6.
- **Writing:** in development.

It runs entirely in the browser, with no account and no install, and it works on a phone.

---

## Why I built it

I had about 25 days before my test and a full working week. The only time I could protect was:

- **Lunch, 12:00–13:00:** reading, which needs focus but no desk.
- **Evenings, 19:00–22:00:** practice tests, timed sections and essay writing.

Flashcards were already covering the bulk of the word list. What I lacked was depth for the hardest words: what each one actually means, how it behaves in a sentence, and how to recall it under pressure. On the writing side I needed models to imitate. Existing resources were either too thin or too long for a one-hour lunch, so I made something that fits that hour exactly.

---

## How to use it

### At lunch: Words (20 words a day, 15 days)

1. Open **Words**. It opens on today's set; use the arrows or the day picker to move between days.
2. Tap each of the 20 word tabs. Every word shows:
   - its US pronunciation (IPA, an easy respelling, and a **speaker button**);
   - its meaning and senses;
   - **5 example sentences**, each with what the sentence means and what the word means *in that sentence*.

   Under **More** you'll find synonyms, look-alike words, a memory hook, a GRE-style practice question and dictionary links.
3. Finish with the 21st tab, **Test your vocab**. It shuffles all 100 example sentences for the day with the word blanked out.
   - Pick from 4 options, or type the word.
   - Missed sentences come back at the end, and the word tabs turn green or red as you go.
   - Switch the pool to "Days 1–N" to review everything so far.

Twenty words with their examples take about 40 minutes. The test takes about 15.

### In spare minutes: Essays

Open **Essays** and read one or two model essays a day. Filter them by instruction type or theme, or search for a word. Each essay shows:

- the prompt and its specific instruction;
- the essay, with the target words highlighted (tap one for its meaning and pronunciation);
- **Why it scores a 6**, covering position, development, organization, language and the specific task;
- paragraph-by-paragraph notes (toggle **Show paragraph notes**);
- **Moves to borrow**, three reusable sentence patterns taken from the essay;
- **What a 4 or 5 would do instead.**

Mark essays as read to track your progress.

### Handy links

Add these to the address to jump straight to a section:

| Link ending | Opens |
|---|---|
| `#d05` | Day 5 of the words |
| `#d05-test` | Day 5's test |
| `#essays` | The essay bank |

Your progress (words seen, test results, essays read) is saved in your own browser on that device.

---

## How the content was made, and checked

- **Words:** chosen as the rarest words on a standard advanced GRE list. Definitions and examples were written in plain English and checked against major learner's dictionaries.
- **Pronunciation:** each word's US pronunciation was transcribed twice independently, and every disagreement was settled against dictionaries. The audio was generated from those transcriptions with an open-source voice model (Kokoro).
- **Essays:** 200 original prompts, spread across the six Issue instruction types.
  - Each essay was scored blind against the published Issue scoring guide.
  - Each was checked for factual accuracy, correct word use and accurate analysis, then fixed.
  - A final, stricter audit re-checked every essay.

If you spot a mistake, please open an issue.

---

## Thank you, Claude

This project would not exist without Claude (Anthropic).
