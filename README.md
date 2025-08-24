# AfricanNLP-progress 🌍

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#how-to-contribute)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](LICENSE)
[![Focus: AfricaNLP](https://img.shields.io/badge/Focus-AfricaNLP-informational.svg)](#scope)
[![Last Updated](https://img.shields.io/badge/last--updated-2025--08--24-black.svg)](#)

> A community-maintained, task-oriented leaderboard of results for **African languages**, starting with **Hausa (ha)**, **Swahili (sw)**, and **Yoruba (yo)**.  
> Inspired by the excellent [NLP-progress] and aligned with ACL/EMNLP reporting norms.

<p align="center">
  <img src="assets/banner.png" alt="AfricanNLP-progress" width="85%"/>
</p>

## Scope

We track paper-reported results for core NLP and speech tasks with **clear dataset splits and metrics**. Initial tasks:

- **Core NLP:** Machine Translation, Sentiment Analysis, Hate Speech
- **Additional (mirroring NLP-progress categories):** Language Modeling, Common Sense Reasoning, Multimodal (e.g., ASR/TTS/Vision+Language)

> Languages covered (v0.1): **Hausa (ha), Swahili (sw), Yoruba (yo)**.  
> We welcome PRs adding more African languages and tasks.

## Quick Links

- **Hausa:**  
  [Machine Translation](hausa/machine_translation.md) ·
  [Sentiment Analysis](hausa/sentiment_analysis.md) ·
  [Hate Speech](hausa/hate_speech.md) ·
  [Language Modeling](hausa/language_modeling.md) ·
  [Common Sense](hausa/common_sense.md) ·
  [Multimodal](hausa/multimodal.md)

- **Swahili:**  
  [Machine Translation](swahili/machine_translation.md) ·
  [Sentiment Analysis](swahili/sentiment_analysis.md) ·
  [Hate Speech](swahili/hate_speech.md) ·
  [Language Modeling](swahili/language_modeling.md) ·
  [Common Sense](swahili/common_sense.md) ·
  [Multimodal](swahili/multimodal.md)

- **Yoruba:**  
  [Machine Translation](yoruba/machine_translation.md) ·
  [Sentiment Analysis](yoruba/sentiment_analysis.md) ·
  [Hate Speech](yoruba/hate_speech.md) ·
  [Language Modeling](yoruba/language_modeling.md) ·
  [Common Sense](yoruba/common_sense.md) ·
  [Multimodal](yoruba/multimodal.md)

## Result Table Schema (All Tasks)

Each task page uses the same schema:

| Rank | Model / System | Dataset (Split) | Metric | Score | Paper (Venue/Year) | Code | Date |
|:---:|---|---|---|---:|---|---|:--:|

- **Metric** must match the task’s primary reporting metric (see each page’s *Metrics* note).  
- **Dataset (Split)** must specify the **test** split used (or test server/hidden).  
- **Date** = date when the result was reported (YYYY-MM-DD).

> ⚠️ **Reproducibility:** Prefer peer-reviewed, clearly specified settings (pretraining, prompts, decoding, seeds). Add notes as needed.

## How to Contribute

See [CONTRIBUTING.md](CONTRIBUTING.md) for:
- adding a new result,
- adding a new task or language,
- formatting & citation style,
- ethical reporting guidelines.

## Citation

If you use this repository, please cite it:

```bibtex
@misc{africanlp_progress_2025,
  title = {AfricanNLP-progress: Community Leaderboards for African Languages},
  author = {Muhammad, Shamsuddeen Hassan and Contributors},
  year = {2025},
  url = {https://github.com/your-org/AfricanNLP-progress}
}
