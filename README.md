# African NLP Progress (africanlpprogress)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-living--document-1)
[![Made with ❤️ by the community](https://img.shields.io/badge/made%20with-%E2%9D%A4%EF%B8%8F%20by%20the%20community-red.svg)](#contributing)

A community-maintained index of datasets and state-of-the-art results in **African languages**.  
Initial languages: **Hausa (hau)** · **Swahili (swa)** · **Yorùbá (yor)**.  
Pull requests welcome—see [CONTRIBUTING.md](CONTRIBUTING.md).

> Prior art: This project is inspired by the excellent **NLP-progress** initiative and follows a similar task-per-page structure with language-scoped leaderboards.

---

## 📚 Table of Contents

- [Scope](#scope)
- [Languages & Tasks](#languages--tasks)
  - [Hausa](hausa/README.md): [Machine Translation](hausa/machine_translation.md) · [Sentiment Analysis](hausa/sentiment_analysis.md) · [Hate Speech](hausa/hate_speech.md)
  - [Swahili](swahili/README.md): [Machine Translation](swahili/machine_translation.md) · [Sentiment Analysis](swahili/sentiment_analysis.md) · [Hate Speech](swahili/hate_speech.md)
  - [Yorùbá](yoruba/README.md): [Machine Translation](yoruba/machine_translation.md) · [Sentiment Analysis](yoruba/sentiment_analysis.md) · [Hate Speech](yoruba/hate_speech.md)
- [How to Contribute](#how-to-contribute)
- [Citing this Repository](#citing-this-repository)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Scope

This repository curates **datasets**, **metrics**, and **leaderboards** for core NLP tasks in African languages. Each page lists:
1) Task definition and recommended metrics  
2) Public datasets with links  
3) A leaderboard of published (or reproducible) results  
4) Reproducibility pointers (code, configs, seeds where available)

> Speech tasks (e.g., ASR) are out-of-scope in the initial release but can be added later. For ASR tracking, see the community tracker **WER are we**.

---

## Languages & Tasks

### Hausa (hau)
- **Machine Translation** → [hausa/machine_translation.md](hausa/machine_translation.md)  
- **Sentiment Analysis** → [hausa/sentiment_analysis.md](hausa/sentiment_analysis.md)  
- **Hate Speech** → [hausa/hate_speech.md](hausa/hate_speech.md)

### Swahili (swa)
- **Machine Translation** → [swahili/machine_translation.md](swahili/machine_translation.md)  
- **Sentiment Analysis** → [swahili/sentiment_analysis.md](swahili/sentiment_analysis.md)  
- **Hate Speech** → [swahili/hate_speech.md](swahili/hate_speech.md)

### Yorùbá (yor)
- **Machine Translation** → [yoruba/machine_translation.md](yoruba/machine_translation.md)  
- **Sentiment Analysis** → [yoruba/sentiment_analysis.md](yoruba/sentiment_analysis.md)  
- **Hate Speech** → [yoruba/hate_speech.md](yoruba/hate_speech.md)

---

## How to Contribute

- Add a result by editing the appropriate `<language>/<task>.md` file and inserting a new row under the correct dataset section.
- Each row **must** include: *Dataset*, *Split/Test set*, *Metric*, *Score*, *Model*, *Paper*, *Code*, *Year*.  
- Follow the exact table column order and formatting in [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Citing this Repository

If you use or extend this index, please cite:

```bibtex
@misc{africanlpprogress2025,
  title        = {African NLP Progress (africanlpprogress)},
  author       = {Community, African NLP},
  year         = {2025},
  howpublished = {\url{https://github.com/<your-org>/africanlpprogress}},
  note         = {A community-maintained index of datasets and results for African languages}
}
