---
title: 'Linguistically-Motivated Classifiers vs. Zero-Shot LLMs: Benchmarking Information Disorder Detection on the Italian InDor Corpus'

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

publication: '**[UNDER REVIEW]** — Submitted to the *Information Disorder Workshop at LREC 2026*'
publication_short: '**[UNDER REVIEW]** LREC 2026 - Information Disorder Workshop'

abstract: 'This study benchmarks a Support Vector Machine (SVM) against a zero-shot Large Language Model (Llama 3) for detecting information disorder in Italian news. Using the InDor corpus, we identify a clear trade-off between conservatism and sensitivity. While the SVM achieved higher raw accuracy (0.61 vs. 0.51), neither surpassed the majority-class accuracy baseline (0.63), highlighting why balanced metrics are required under class skew. The SVM acted as a conservative filter, relying on surface cues to protect legitimate news but missing nearly half the problematic content (0.55 recall). Conversely, Llama 3 operated as a high-recall detector, trading overall accuracy for superior sensitivity (0.82 recall). Llama 3 successfully detected camouflaged manipulations missed by the baseline, though it produced more false positives. Qualitative analysis confirms the SVM overfits to dataset-specific keywords, whereas the LLM leverages deeper semantic reasoning. We conclude that SVMs offer stable, low-cost filtering for overt signals, while Llama 3 excels when maximizing the detection of complex deceptive narratives is the primary goal.'

summary: 'A benchmarking study comparing linguistically-motivated classifiers against zero-shot LLMs for detecting information disorder within the Italian InDor corpus, highlighting a trade-off between conservative filtering and high-recall detection.'

tags:
  - LLM
  - Information Disorder
  - Fake News
  - LREC 2026
  - SVM

featured: true

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
