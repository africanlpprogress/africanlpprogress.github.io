# Tracking Progress in African Natural Language Processing

## Table of contents

### Hausa
  [Machine translation](hausa/machine_translation.md) | [Sentiment analysis](hausa/sentiment_analysis.md) | [Hate/abusive speech](hausa/hate_speech.md)
  | [Language modeling](hausa/language_modeling.md) | [Common sense](hausa/common_sense.md) | [Multimodal](hausa/multimodal.md)

### Swahili
  * [Machine translation](swahili/machine_translation.md)
  * [Sentiment analysis](swahili/sentiment_analysis.md)
  * [Hate/abusive speech](swahili/hate_speech.md)
  * [Language modeling](swahili/language_modeling.md)
  * [Common sense](swahili/common_sense.md)
  * [Multimodal](swahili/multimodal.md)

### Yoruba
  * [Machine translation](yoruba/machine_translation.md)
  * [Sentiment analysis](yoruba/sentiment_analysis.md)
  * [Hate/abusive speech](yoruba/hate_speech.md)
  * [Language modeling](yoruba/language_modeling.md)
  * [Common sense](yoruba/common_sense.md)
  * [Multimodal](yoruba/multimodal.md)

---

This document tracks progress in **African NLP** by summarizing benchmark datasets and **state-of-the-art (SOTA)** results for common tasks across Hausa, Swahili, and Yoruba. As with similar efforts, we aim to provide a concise, task-centric entry point and point readers to official leaderboards when those exist and are actively maintained. :contentReference[oaicite:1]{index=1}

If a public leaderboard exists and is regularly updated for a task, we link to it directly from the task page rather than duplicating maintenance here. :contentReference[oaicite:2]{index=2}

---

### Contributing

#### Guidelines

- **Results.** Prefer results reported in peer-reviewed publications; high-impact preprints are acceptable if methods and evaluation are clear.
- **Datasets.** Add datasets that have seen evaluation in at least one paper beyond the introduction paper.
- **Code.** Link to implementations where available. If a `Code` column is present, mark **Official** implementations explicitly and use a regular link for unofficial ones.

These guidelines mirror the proven process in similar SOTA repositories, adapted to African-language tasks. :contentReference[oaicite:3]{index=3}

#### Adding a new result

1. Open the Markdown file for the **language + task** (e.g., `hausa/machine_translation.md`).
2. Insert a new row following the canonical table schema on that page.
3. Keep the table sorted (best score at the top; invert for lower-is-better metrics like perplexity or WER).
4. Use **YYYY-MM-DD** for the Date column and include a venue tag (e.g., `ACL 2025`).
5. Preview your change, then open a pull request.

#### Adding a new dataset or task

1. If the task is **new**, create a new task file under each relevant language directory and link it in this **Table of contents**.
2. Briefly describe the dataset/task, provide references, define the evaluation setting and **primary metric**.
3. Include an example (if space allows) and a download link (if available).
4. Add a results table with **at least two** entries (including the SOTA), using the standard schema.
5. Submit a pull request.

---

### Wish list

These tasks/datasets are especially valuable to add for African languages:

- Named entity recognition (NER)
- Part-of-speech tagging (POS)
- Question answering (extractive & open-domain)
- Summarization (news, social, conversation)
- Natural language inference (NLI)
- Semantic textual similarity (STS)
- Dialogue and intent/slot (task-oriented, open-domain)
- Discourse parsing
- Keyphrase extraction
- Topic classification beyond sentiment/hate
- Speech tasks beyond ASR/TTS (e.g., keyword spotting)

(Contributors: feel free to open an issue proposing additional priorities.)

---

### Exporting into a structured format

We plan to provide a script to export all task tables into a **machine-readable JSON** (tasks, datasets, metrics, and SOTA entries) to facilitate dashboards and meta-analysis. See `structured/README.md` (coming soon) for instructions based on a workflow similar to related projects. :contentReference[oaicite:4]{index=4}

---

### Instructions for building the site locally

If you’d like to serve these pages via GitHub Pages (Jekyll):

1. Ensure Ruby and Bundler are installed.
2. From the repo root: `bundle install` then `bundle exec jekyll serve`.
3. Open `http://localhost:4000/` and verify internal links render as expected.

For a reference workflow and configuration layout, see the analogous instructions in the original SOTA repository. :contentReference[oaicite:5]{index=5}

---

## About

**AfricanNLP-progress** is a community-maintained index of datasets and SOTA results for African languages, starting with Hausa, Swahili, and Yoruba. It is inspired by and structurally aligned with **NLP-progress**. We thank that community for the template and the broader vision behind tracking field progress. :contentReference[oaicite:6]{index=6}

**License:** See `LICENSE` (CC BY 4.0 or as set by this repository).

