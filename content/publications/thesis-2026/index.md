---
title: 'Culturally Adaptive Explainable LLM Assessment for Multilingual Information Disorder'
authors:
  - me
date: '2026-07-10T00:00:00Z'
publishDate: '2026-07-10T00:00:00Z'
publication_types: ['7']
publication: "*Master's Thesis, University of Turin*"
publication_short: "*Master's Thesis, University of Turin*"
abstract: >
  Information disorder, understood as the deliberate or incidental spread of misleading, manipulative, or decontextualized content, does not manifest the same way across languages and cultures. The rhetorical strategies, ideological markers, and framing patterns that signal bias in one linguistic community may read as neutral reporting in another. Yet most automated detection systems apply the same models and reasoning patterns regardless of cultural context, producing what this thesis terms *culturally misaligned rationales*: fluent explanations that fail to engage with the specific discursive and cultural logic of the target community. Current large language models are predominantly English-centric and monocultural in their explanatory reasoning, and this thesis argues that addressing *cultural blindness* in automated information disorder assessment requires moving beyond static few-shot prompting toward community-aligned adaptive approaches.

  To this end, a Culturally Adaptive Retrieval-Based Framework is proposed and evaluated. The framework uses semantic retrieval over a community-annotated exemplar bank to dynamically align model reasoning with culturally relevant examples at inference time. A pilot study is conducted on the InDor corpus across Farsi (Persian) and Italian using LLaMA 4 Maverick and Mixtral-8x22B-Instruct, comparing four prompting conditions across three evaluation tasks: severity classification, span detection, and rationale generation quality.

  On automatic metrics, the framework shows its clearest benefit in Farsi, where retrieval improved span detection and rationale quality across both models and severity classification for Maverick. Italian results were more mixed, with severity improving under Maverick but rationale quality favouring the static baseline for that model. Beyond automatic metrics, native speakers of both languages rated retrieval-based rationales higher than the static baseline in a blind A/B human evaluation, with the improvement more pronounced in Farsi. The study also surfaces emergent model behaviors with broader implications for deploying instruction-tuned models on sensitive analytical tasks. Overall, the results show encouraging signs that aligning model reasoning with community-annotated exemplars moves outputs closer to what native speakers recognize as appropriate analysis, and are best read as a meaningful first step on a genuinely difficult and under-explored problem. The framework is designed as a foundation for a broader human-in-the-loop integration, where iterative community feedback can progressively refine the exemplar bank and improve cultural alignment over time. All code, prompts, evaluation scripts, and supplementary resources (including a curated landscape review of 108 fake news and information disorder datasets) are made publicly available as a community resource to support reproducibility, future extension, and broader adoption of culturally adaptive evaluation approaches.
tags:
  - Information Disorder
  - Multilingual NLP
  - Explainable AI
  - Human-in-the-Loop
  - Cultural Bias
featured: true
url_pdf: 'https://maziarkiani.github.io/uploads/thesis.pdf'
url_code: 'https://github.com/Maziarkiani/culturally-adaptive-prompting'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://hdl.handle.net/20.500.14240/192055'
url_video: ''
---


## How to Cite This Work

Kianimoghadam Jouneghani, M. (2026). Culturally Adaptive Explainable LLM Assessment for Multilingual Information Disorder (Master’s thesis, University of Turin). Advisors: Viviana Patti and
Marco Antonio Stranisci. Full text available at https://maziarkiani.github.io/uploads/thesis.pdf UniTesi handle: https://hdl.handle.net/20.500.14240/192055

```bibtex
@mastersthesis{kianimoghadam2026culturally,
  title   = {Culturally Adaptive Explainable LLM Assessment for Multilingual Information Disorder},
  author  = {Kianimoghadam Jouneghani, Maziar},
  year    = {2026},
  school  = {University of Turin},
  type    = {Master's thesis},
  address = {Turin, Italy},
  note    = {Advisors: Viviana Patti and Marco Antonio Stranisci. 
             UniTesi handle: https://hdl.handle.net/20.500.14240/192055},
  url     = {https://maziarkiani.github.io/uploads/thesis.pdf}
}
```
