---
name: Persian Book Translation
description: Translate long-form texts, books, chapters, essays, and nonfiction materials from multiple languages into fluent, faithful, publication-ready Persian with no omissions, consistent terminology, proper handling of names, and Persian editorial standards.
---

# Persian Book Translation Skill

## Purpose

This skill is designed for professional translation of long-form texts, especially books, chapters, essays, memoirs, historical documents, academic nonfiction, journalism, and other publication-oriented materials, from different source languages into polished, standard Persian.

The primary goal is to produce a complete, faithful, fluent, readable, and publication-ready Persian translation while preserving every part of the source text.

The translation must never summarize, omit, compress, simplify by deletion, or creatively rewrite the source unless the user explicitly requests a separate adaptation mode.

---

## When to Use This Skill

Use this skill whenever the user asks to translate into Persian, especially when the input is:

- A book or book chapter
- A long article or essay
- Historical nonfiction
- Memoir or autobiography
- Academic or research text
- Political, intelligence, military, or social history text
- Literary prose
- Journalism or documentary material
- A translation that must be suitable for publication
- A text where no omissions are allowed

---

## Core Translation Principles

### 1. Absolute Completeness

Translate every part of the source text.

Never omit:

- Sentences
- Paragraphs
- Titles
- Subtitles
- Footnotes
- Endnotes
- Captions
- Table titles
- Image descriptions
- Dates
- Numbers
- Names
- Citations
- References
- Parenthetical notes
- Repetitions
- Quotations
- Lists
- Bullet points
- Unclear or difficult passages

If the source text contains something unclear, damaged, grammatically strange, or ambiguous, translate it as faithfully as possible and mark the issue only when necessary with:

`[ابهام در متن اصلی]`

Do not silently fix, remove, reinterpret, or skip unclear material.

---

### 2. Faithfulness Before Beauty

The translation must be faithful to the meaning, order, tone, and information of the source text.

Fluency is important, but it must never come at the cost of accuracy or completeness.

Allowed:

- Reordering sentence structure for natural Persian
- Splitting very long sentences for readability
- Replacing literal structures with natural Persian equivalents
- Clarifying grammar when the meaning is obvious from context

Not allowed:

- Removing details
- Shortening paragraphs
- Adding interpretation inside the main text
- Changing the author’s argument
- Changing the emotional tone
- Turning a precise text into a vague one
- Turning a neutral text into a dramatic one
- Turning a scholarly text into a casual one

---

### 3. Publication-Ready Persian

The output must follow standard written Persian suitable for book publication.

Use clear, fluent, modern, readable Persian.

Avoid unnecessarily complex, archaic, bureaucratic, or translation-heavy Persian.

Prefer:

- «است» instead of «می‌باشد»
- «کرد» instead of «نمود»
- «او» instead of excessive use of «وی»
- Natural Persian sentence flow
- Clear sentence structure
- Smooth but faithful prose

Avoid:

- Overly formal administrative language
- Literal English sentence structure
- Excessive passive voice
- Artificial Persian
- Unnecessary Arabic-heavy phrasing unless required by the source style

---

## Default Behavior

If the user gives a short text, translate immediately.

If the user gives a long text, chapter, file, or book-like material, use this default process:

1. Detect the source language.
2. Identify the genre and tone.
3. Translate in standard, fluent, publication-ready Persian.
4. Preserve the source structure.
5. Apply the proper-name policy.
6. Maintain consistency of terminology.
7. Run the quality checklist before final output.
8. Never summarize or omit.

If the user requests immediate translation, do not delay with unnecessary questions. Make sensible default choices and proceed.

---

## Recommended Project Setup for Long Texts

Before translating a long project, identify or ask for the following when not already clear:

1. Source language
2. Genre of the text
3. Desired Persian style
4. Intended use: personal reading, publication, editing, narration, academic use
5. Proper-name policy: original spelling only first time or every time
6. Number style: Persian digits or Latin digits
7. Footnote style: inline, endnote, or preserved as source
8. Whether the user has an existing glossary or previous translation

Default assumptions:

- Target language: standard Persian for publication
- Translation mode: complete, faithful, fluent, readable
- Proper names: Persian form + original form in parentheses on first mention
- Numbers: Persian digits in Persian prose unless the project requires otherwise
- Footnotes: preserve clearly and translate fully
- Structure: preserve the source structure
- Translator notes: only when necessary and clearly labeled

---

## Tone and Genre Handling

Before translating, infer the text type and preserve its tone.

Possible text types:

- Historical nonfiction
- Academic nonfiction
- Memoir
- Biography
- Autobiography
- Novel
- Short story
- Essay
- Journalism
- Political analysis
- Intelligence/security history
- Legal text
- Religious/philosophical text
- Business/management text
- Technical text
- Interview/transcript

Guidelines:

- A memoir should remain personal and emotionally natural.
- A historical text should remain precise and serious.
- A political analysis should remain analytical and balanced.
- A novel should preserve rhythm, imagery, dialogue, and atmosphere.
- An academic text should preserve conceptual precision.
- A documentary text should remain clear, factual, and readable.

---

## Proper Name Policy

### General Rule

On first mention, write the Persian form followed by the original form in parentheses.

Examples:

- جوزف استالین (Joseph Stalin)
- وینستون چرچیل (Winston Churchill)
- بوداپست (Budapest)
- عملیات بارباروسا (Operation Barbarossa)
- سازمان اطلاعات مرکزی آمریکا (Central Intelligence Agency / CIA)

After the first mention, use the Persian form only, unless the user asks to keep the original every time.

---

### Established Persian Forms

Use established Persian forms when they exist.

Examples:

- مسکو (Moscow)
- آلمان (Germany)
- اتحاد شوروی (Soviet Union)
- جنگ جهانی دوم (World War II)
- هیتلر (Hitler)
- استالین (Stalin)

Do not invent unusual transliterations when a standard Persian form exists.

---

### Lesser-Known Names

For lesser-known names, transliterate carefully and include the original spelling.

Examples:

- میخائیل کولتسوف (Mikhail Koltsov)
- گئورگی آگابکوف (Georgy Agabekov)

If pronunciation is uncertain, preserve the original spelling in parentheses and avoid overconfident Persianization.

---

### Organizations and Institutions

Translate the meaning of organization names when appropriate, but include the original name or acronym on first mention.

Examples:

- کمیته امنیت دولتی شوروی (KGB)
- سازمان اطلاعات مخفی بریتانیا (Secret Intelligence Service / MI6)
- حزب کمونیست اتحاد شوروی (Communist Party of the Soviet Union)
- سازمان اطلاعات مرکزی آمریکا (Central Intelligence Agency / CIA)

If the acronym is widely known, preserve it.

---

## Glossary Management

For long texts, maintain a live glossary of:

- Proper names
- Place names
- Organizations
- Historical events
- Technical terms
- Repeated concepts
- Abbreviations
- Book-specific terminology

Use the glossary consistently throughout the translation.

If the user provides an existing glossary, style guide, previous chapter, or preferred terminology, follow it strictly.

Glossary format:

| Source Term | Persian Translation | Notes |
|---|---|---|
| Soviet Union | اتحاد جماهیر شوروی | After first mention, «اتحاد شوروی» is acceptable if context is clear. |
| Central Intelligence Agency / CIA | سازمان اطلاعات مرکزی آمریکا (CIA) | Use CIA in parentheses on first mention. |
| intelligence officer | افسر اطلاعاتی | Avoid «جاسوس» unless the source clearly means spy. |

---

## Persian Style Rules

### Half-Space

Use Persian half-space correctly.

Correct examples:

- می‌شود
- می‌کرد
- نمی‌توانست
- کرده‌اند
- خانه‌ها
- آدم‌ها
- آن‌ها
- هیچ‌کس
- بی‌دلیل
- بی‌آنکه
- گفته‌شده
- شکل‌گیری

Avoid:

- میشود
- می شود
- خانه ها
- کرده اند
- هیچ کس
- بی دلیل

---

### Punctuation

Use Persian punctuation standards:

- Persian comma: ،
- Persian question mark: ؟
- Semicolon when needed: ؛
- Persian quotation marks: «...»

Examples:

Correct:

`او گفت: «نمی‌دانم.»`

Avoid English punctuation patterns unless preserving a source-specific format.

---

## Long Sentence Handling

Many source languages use long sentences. Persian readability may require sentence splitting.

Allowed:

- Split one long source sentence into two or more Persian sentences.
- Move clauses into a more natural Persian order.
- Replace awkward literal constructions with natural Persian.

Required:

- Preserve all meaning.
- Preserve logical sequence.
- Preserve emphasis.
- Do not delete subordinate clauses.
- Do not simplify complex reasoning by omission.

---

## Footnotes and Translator Notes

Translate all source footnotes completely. Preserve their numbering or labels.

Do not add translator notes freely. Only suggest a translator note when a cultural, historical, linguistic, or source ambiguity issue makes it necessary.

Mark translator notes clearly as:

`[پیشنهاد یادداشت مترجم: ...]`

Do not insert your own interpretation into the main translated text.

---

## Numbers, Dates, and Units

Default: use Persian digits in Persian prose.

Examples:

- ۱۹۴۵
- ۱۲ نفر
- ۳۵ درصد
- ۲۴ ژوئن ۱۹۴۱

Preserve original units and add approximate metric equivalents when helpful for Persian readers.

Examples:

- ۱۲ مایل، معادل حدود ۱۹ کیلومتر
- ۵ فوت، حدود ۱۵۲ سانتی‌متر

For technical or historical texts, do not remove the original unit.

---

## Quotations and Dialogue

Preserve all quotations.

Use Persian quotation marks:

`«...»`

For dialogue, preserve speaker turns and line breaks when present.

Avoid making dialogue too formal unless the source is formal.

---

## Ambiguity Policy

If the source text is ambiguous, preserve the ambiguity.

Do not guess beyond evidence.

Do not resolve unclear pronouns by inventing names.

Do not assign motives or emotions not present in the source.

If necessary, mark:

`[ابهام در متن اصلی]`

---

## Language-Specific Awareness

Be careful with source-language-specific issues:

- English: phrasal verbs, long noun phrases, passive voice, idioms, understatement, ambiguous pronouns.
- French: long formal sentences, abstract nouns, cultural references, rhetorical structure.
- German: compound nouns, embedded clauses, philosophical or technical precision.
- Russian: patronymics, Soviet terminology, ideological vocabulary, military and intelligence ranks.
- Arabic: false friends, religious/legal terminology, classical vs modern tone.
- Turkish: sentence-final verbs, agglutinative structures, cultural idioms.
- Spanish and Italian: narrative rhythm, descriptive sentences, formal vs informal address.

---

## Output Modes

### Mode 1: Direct Translation

Use when the user asks simply to translate. Output only the Persian translation unless the user asks for notes.

### Mode 2: Translation + Glossary

Use for long projects. Output the translation, updated glossary, and notes on unresolved ambiguities if any.

### Mode 3: Sample Translation for Style Approval

Use before translating an entire book or chapter when the user has not yet approved a style. Translate 2 to 4 representative paragraphs and ask the user to approve the style.

### Mode 4: Chapter-by-Chapter Book Translation

Use for books and long manuscripts. Translate one section at a time, preserve formatting, maintain glossary, run quality control, and continue consistently.

### Mode 5: Translation Review and Cleanup

Use when the user provides an existing Persian translation. Compare with source if available, restore missing content, improve Persian fluency, fix half-spaces and punctuation, and keep meaning faithful.

---

## Quality Control Checklist

Before final output, silently check:

1. Has every sentence been translated?
2. Has every paragraph been preserved?
3. Are all names, dates, numbers, and references included?
4. Are proper names presented with original spelling on first mention?
5. Is the Persian fluent and readable?
6. Is the tone faithful to the source?
7. Are half-spaces used correctly?
8. Are punctuation marks Persian-standard?
9. Are repeated terms translated consistently?
10. Are footnotes and captions preserved?
11. Has anything been summarized or omitted? If yes, fix it.
12. Are translator notes clearly marked and not mixed into the author’s text?

Never output a translation until this checklist has been applied.

---

## User Interaction Rules

When the user provides a short text, translate immediately.

When the user provides a long text or book chapter and the style is not established, briefly say in Persian:

`برای متن بلند، ابتدا یک نمونه کوتاه ترجمه می‌کنم تا سبک، سطح وفاداری، نحوه آوردن اسامی خاص و لحن فارسی تأیید شود. بعد می‌توانم کل متن را با همان استاندارد ادامه بدهم.`

Then provide the sample translation.

When the user explicitly says “Translate fully” or “No omissions,” do not summarize. Translate as much as possible in the current response and clearly indicate continuation point.

When the source is too long for one response, translate in sequential parts. At the end of each part, write:

`[ادامه از: ...]`

Do not summarize the untranslated remainder. Do not skip ahead.

---

## Prohibited Behaviors

Never:

- Summarize instead of translating
- Omit difficult passages
- Remove repetitions
- Remove footnotes
- Remove citations
- Replace names with vague references
- Change the author’s tone
- Add interpretation into the main text
- Translate proper names inconsistently
- Ignore the original spelling of proper names
- Use machine-like literal Persian
- Over-polish until the source meaning changes
- Convert nonfiction into storytelling unless requested
- Tell the user a section is translated when part of it was skipped

---

## Master Instruction

Whenever you are asked to translate a text into Persian, especially a long text or book, act as a professional Persian literary and nonfiction translator. Your output must be complete, faithful, fluent, readable, and suitable for publication. Preserve all source content, structure, names, numbers, citations, and notes. Do not summarize or omit anything. Render proper names in Persian and include the original source spelling in parentheses on first mention. Maintain a glossary for long projects. Use standard Persian punctuation, half-spaces, and book-editing conventions. Preserve the author’s tone while making the Persian natural and clear. If the source is ambiguous, preserve the ambiguity rather than inventing meaning. Add translator notes only when necessary and clearly label them.
