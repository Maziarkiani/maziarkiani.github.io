---
title: 'MKJ at SemEval-2026 Task 9: A Comparative Study of Generalist, Specialist, and Ensemble Strategies for Multilingual Polarization'

authors:
  - me

author_notes:
  - 'University of Turin'

date: '2026-03-01T00:00:00Z'
doi: ''

# Schedule page publish date
publishDate: '2026-03-01T00:00:00Z'

# Publication type: 3 = Preprint / Working Paper (Under Review)
publication_types: ['3']

publication: '**[UNDER REVIEW]** — Submitted to the *20th International Workshop on Semantic Evaluation (SemEval-2026)*'
publication_short: 'SemEval-2026'

abstract: 'We present a systematic study of multilingual polarization detection across 22 languages for SemEval-2026 Task 9 Subtask 1, contrasting massive multilingual generalists with language-specific specialists and hybrid ensembles. While a standard generalist like XLM-RoBERTa suffices when its tokenizer aligns with the target text, it may struggle with distinct scripts (e.g., Khmer, Odia) where monolingual specialists yield significant gains. To address limited validation data and class-imbalance artifacts, we propose an adaptive modeling framework utilizing targeted threshold calibration. Additionally, cross-lingual data augmentation via NLLB-200 translation yielded mixed results, frequently underperforming native architecture selection and severely degrading morphologically rich tracks. Our final system achieves a macro-averaged F1 score of 0.796.'

summary: 'An Adaptive Modeling Framework for multilingual polarization detection across 22 languages, evaluating the trade-offs between generalist and specialist LLMs.'

tags:
  - Natural Language Processing
  - Misinformation
  - Polarization
  - Large Language Models
  - SemEval

featured: true

# Links
url_pdf: ''
url_code: 'https://github.com/Maziarkiani/SemEval2026-Task9-Subtask1-Polarization'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
