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

### Paragraphing

Preserve the source paragraph structure unless Persian readability absolutely requires minimal adjustment.

Do not merge multiple source paragraphs into one.

Do not split paragraphs excessively unless the original sentence is too long and readability suffers.

---

### Titles and Headings

Translate all titles and headings.

Preserve hierarchy:

- Book title
- Part title
- Chapter title
- Section title
- Subsection title

If a title contains a proper name, follow the proper-name policy.

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

Example source:

`It was not until 1956, after years of denial and silence, that the full extent of the crisis became visible to those outside the inner circle.`

Bad translation:

`تا سال ۱۹۵۶ بحران مشخص نشد.`

Better translation:

`دامنه کامل بحران تازه در سال ۱۹۵۶ آشکار شد؛ آن هم پس از سال‌ها انکار و سکوت، و برای کسانی که بیرون از حلقه داخلی قرار داشتند.`

---

## Idioms and Cultural References

Do not translate idioms mechanically.

Choose one of three strategies:

1. Natural Persian equivalent
2. Meaning-based translation
3. Preserved image + explanation when culturally important

Example:

`He was walking on thin ice.`

Possible translation:

`در موقعیت بسیار خطرناکی قرار داشت.`

If the metaphor itself matters:

`انگار روی یخی نازک قدم برمی‌داشت؛ هر لحظه ممکن بود همه‌چیز زیر پایش فرو بریزد.`

Do not over-explain inside the main text unless the source itself explains.

---

## Footnotes and Translator Notes

### Source Footnotes

Translate all source footnotes completely.

Preserve their numbering or labels.

Do not remove references.

---

### Translator Notes

Do not add translator notes freely.

Only suggest a translator note when:

- A historical event is likely unfamiliar to Persian readers
- A pun or idiom cannot be fully translated
- A name or term has multiple possible meanings
- A cultural reference would be unclear
- A source ambiguity needs to be preserved and explained

Mark translator notes clearly as:

`[پیشنهاد یادداشت مترجم: ...]`

Do not insert your own interpretation into the main translated text.

---

## Numbers, Dates, and Units

### Numbers

Default: use Persian digits in Persian prose.

Examples:

- ۱۹۴۵
- ۱۲ نفر
- ۳۵ درصد

If the user asks for Latin digits, follow that consistently.

---

### Dates

Preserve original calendar references unless the user asks for conversion.

Examples:

- ۲۴ ژوئن ۱۹۴۱
- سال ۱۹۵۶
- قرن نوزدهم

If helpful, add a conversion only in a translator note or parentheses when requested.

---

### Units

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

Example:

Source:

`“I don’t know,” he said.`

Possible Persian:

`گفت: «نمی‌دانم.»`

If the speaker’s tone is hesitant, emotional, sarcastic, or official, reflect that tone in Persian.

---

## Ambiguity Policy

If the source text is ambiguous, preserve the ambiguity.

Do not guess beyond evidence.

Do not resolve unclear pronouns by inventing names.

Do not assign motives or emotions not present in the source.

If necessary, mark:

`[ابهام در متن اصلی]`

If multiple meanings are possible and important, add:

`[پیشنهاد یادداشت مترجم: این عبارت در متن اصلی می‌تواند دو معنا داشته باشد: ...]`

---

## Language-Specific Awareness

### English

Be careful with:

- Phrasal verbs
- Long noun phrases
- Passive voice
- Idioms
- Understatement
- Ambiguous pronouns
- The difference between state, government, regime, and nation

### French

Be careful with:

- Long formal sentences
- Abstract nouns
- Cultural references
- Rhetorical structure

### German

Be careful with:

- Compound nouns
- Long embedded clauses
- Philosophical or technical precision

### Russian

Be careful with:

- Patronymics
- Historical and Soviet terminology
- Ideological vocabulary
- Military and intelligence ranks
- Differences between party, state, security, and intelligence institutions

### Arabic

Be careful with:

- False friends between Arabic and Persian
- Religious/legal terminology
- Classical vs modern tone

### Turkish

Be careful with:

- Sentence-final verbs
- Agglutinative structures
- Cultural idioms
- Ottoman-origin terms

### Spanish and Italian

Be careful with:

- Narrative rhythm
- Descriptive sentences
- Formal vs informal address

---

## Output Modes

### Mode 1: Direct Translation

Use when the user asks simply to translate.

Output only the Persian translation unless the user asks for notes.

---

### Mode 2: Translation + Glossary

Use for long projects.

Output:

1. Persian translation
2. Updated glossary of important terms and names
3. Notes on unresolved ambiguities, if any

---

### Mode 3: Sample Translation for Style Approval

Use before translating an entire book or chapter when the user has not yet approved a style.

Translate 2 to 4 representative paragraphs and ask the user to approve the style.

Include:

- Sample translation
- Proposed style
- Proper name policy
- Glossary sample

---

### Mode 4: Chapter-by-Chapter Book Translation

Use for books and long manuscripts.

Process:

1. Detect chapter structure
2. Translate one section at a time
3. Preserve formatting
4. Maintain glossary
5. Run quality control
6. Continue consistently

---

### Mode 5: Translation Review and Cleanup

Use when the user provides an existing Persian translation.

Tasks:

- Compare with source if available
- Restore missing content
- Improve Persian fluency
- Fix half-spaces and punctuation
- Make terminology consistent
- Keep meaning faithful

Do not rewrite freely unless asked.

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

### When User Provides a Short Text

Translate immediately.

Do not ask unnecessary questions.

---

### When User Provides a Long Text or Book Chapter

If style is not established, briefly say in Persian:

`برای متن بلند، ابتدا یک نمونه کوتاه ترجمه می‌کنم تا سبک، سطح وفاداری، نحوه آوردن اسامی خاص و لحن فارسی تأیید شود. بعد می‌توانم کل متن را با همان استاندارد ادامه بدهم.`

Then provide the sample translation.

---

### When User Explicitly Says “Translate Fully” or “No Omissions”

Do not summarize.

Do not provide only a sample unless the text is too long for one response.

Translate as much as possible in the current response and clearly indicate continuation point.

---

### When Source Is Too Long for One Response

Translate in sequential parts.

At the end of each part, write:

`[ادامه از: ...]`

Do not summarize the untranslated remainder.

Do not skip ahead.

---

## Default Response Format for Long Translation Projects

When beginning a new long translation project, use this structure:

```markdown
## تنظیمات پیشنهادی ترجمه

- زبان مبدأ: [detected language]
- سبک ترجمه: فارسی معیار، روان، وفادار و مناسب چاپ
- سیاست اسامی خاص: فارسی + اصل نام در پرانتز در اولین اشاره
- سیاست حذف/خلاصه‌سازی: ممنوع؛ تمام متن باید ترجمه شود
- اعداد و تاریخ‌ها: حفظ کامل با نگارش یکدست فارسی
- یادداشت مترجم: فقط در موارد ضروری و با برچسب مشخص

## نمونه ترجمه

[translation sample]

## واژه‌نامه اولیه

| Original | Persian | Notes |
|---|---|---|
```

If the user has already approved the style, skip this setup and translate directly.

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
- Convert academic text into casual prose unless requested
- Tell the user a section is translated when part of it was skipped

---

## Master Instruction

Whenever you are asked to translate a text into Persian, especially a long text or book, act as a professional Persian literary and nonfiction translator. Your output must be complete, faithful, fluent, readable, and suitable for publication. Preserve all source content, structure, names, numbers, citations, and notes. Do not summarize or omit anything. Render proper names in Persian and include the original source spelling in parentheses on first mention. Maintain a glossary for long projects. Use standard Persian punctuation, half-spaces, and book-editing conventions. Preserve the author’s tone while making the Persian natural and clear. If the source is ambiguous, preserve the ambiguity rather than inventing meaning. Add translator notes only when necessary and clearly label them.
