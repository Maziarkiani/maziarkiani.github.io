---
title: "MKJ at SemEval-2026 Task 9: A Comparative Study of Generalist, Specialist, and Ensemble Strategies for Multilingual Polarization"

authors:
  - me

date: "2026-04-13T00:00:00Z"
publishDate: "2026-04-13T00:00:00Z"

doi: "10.18653/v1/2026.semeval-1.181"

# Publication type: 1 = Conference paper
publication_types:
  - "1"

publication: "Proceedings of the 20th International Workshop on Semantic Evaluation (SemEval-2026)"
publication_short: "*SemEval-2026*"
abstract: "We present a systematic study of multilingual polarization detection across 22 languages for SemEval-2026 Task 9 (Subtask 1), contrasting multilingual generalists with language-specific specialists and hybrid ensembles. While a standard generalist like XLM-RoBERTa suffices when its tokenizer aligns with the target text, it may struggle with distinct scripts (e.g., Khmer, Odia) where monolingual specialists yield significant gains. Rather than enforcing a single universal architecture, we adopt a language-adaptive selection strategy that chooses among multilingual generalists, language-specific specialists, and hybrid ensembles based on development performance. Additionally, cross-lingual augmentation via NLLB-200 yielded mixed results, often underperforming native architecture selection and degrading morphologically rich tracks. Our final system achieves an overall macro-averaged F1 score of 0.796 and an average accuracy of 0.826 across all 22 tracks. Code and final test predictions are publicly available at: https://github.com/Maziarkiani/SemEval2026-Task9-Subtask1-Polarization."

summary: "A language-adaptive modeling framework for multilingual polarization detection across 22 languages, evaluating the trade-offs between multilingual generalists, language-specific specialists, and ensemble methods."

tags:
  - Natural Language Processing
  - Polarization Detection
  - SemEval 2026

featured: true

# Links
url_pdf: "https://aclanthology.org/2026.semeval-1.181/"
url_code: "https://github.com/Maziarkiani/SemEval2026-Task9-Subtask1-Polarization"
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: "https://aclanthology.org/2026.semeval-1.181/"
url_video: ""
---
