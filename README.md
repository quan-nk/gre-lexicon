# GRE Lexicon

**Live site:** https://quan-nk.github.io/gre-lexicon/

A small, self-contained study app I built to prepare for GRE Verbal around a full-time job. It has three parts:

- **Words:** 300 advanced GRE words with US pronunciation, plain-English meanings, example sentences and a mixed recall test.
- **Essays:** every topic in the official ETS "Analyze an Issue" pool (158), each with two model essays (one per side) written to a single 5-paragraph template, plus the template itself, a phrase bank and topic synonyms.
- **Writing:** grammar drills, a writing toolkit and a progress log. Timed writing and feedback are in development.

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

Start with **Template**: the 5-paragraph structure (intro, two body paragraphs, a concession, a conclusion), how it adapts to each of the six instruction types, a 30-minute plan and a bank of go-to examples.

Then read one or two topics a day under **Essays**. Every topic in the official pool has two essays of about 600 words, one for each side, so you see how the same template argues either way. In each essay:

- **Show structure** labels every sentence with its job (hook, thesis, topic sentence, example, development, concession, rebuttal…);
- vocabulary words are highlighted (tap one for its meaning and pronunciation);
- a note explains how the essay follows that topic's specific instruction.

**Phrases** gives 8–12 variants for every slot of the template, and **Topic words** gives synonyms for the ideas the pool keeps returning to. Mark essays as read to track your progress.

### Before an essay: Writing

- **Drills.** *Error hunt* gives 15 sentences: tap the word that holds the error, or "No error". It leans toward the error types you miss most. *Article lab* gives 8 sentences: choose a, an, the or no article for each blank.
- **Toolkit.** The 30-minute plan, the 4-minute proofread (five scans, in order), the six instruction types, common Vietnamese-to-English traps and the 12 error codes.
- **Progress.** Your drill accuracy by error type, plus your official POWERPREP writing scores if you log them.

### Handy links

Add these to the address to jump straight to a section:

| Link ending | Opens |
|---|---|
| `#d05` | Day 5 of the words |
| `#d05-test` | Day 5's test |
| `#essays` | The pool topics and essays |
| `#essays-template` | The essay template |
| `#drills` | Writing drills |
| `#toolkit` | Writing toolkit |

Your progress (words seen, test results, essays read, drill scores) is saved in your own browser on that device.

---

## How the content was made, and checked

- **Words:** chosen as the rarest words on a standard advanced GRE list. Definitions and examples were written in plain English and checked against major learner's dictionaries.
- **Pronunciation:** each word's US pronunciation was transcribed twice independently, and every disagreement was settled against dictionaries. The audio was generated from those transcriptions with an open-source voice model (Kokoro).
- **Essays:** all 158 topics in ETS's published Issue pool, two essays each.
  - Each essay was checked by a separate reviewer for following the topic's instruction, length, organization, cohesion and language, and fixed where needed.
  - A script also checks every essay's length, paragraph structure and vocabulary markup.
  - Examples come from a short bank of fact-checked cases, so the facts stay right and the examples are reusable on test day.

If you spot a mistake, please open an issue.

---

## Thank you, Claude

This project would not exist without Claude (Anthropic).
