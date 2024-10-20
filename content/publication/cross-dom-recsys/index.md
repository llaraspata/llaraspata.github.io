---
title: 'Instructing and Prompting Large Language Models for Explainable Cross-domain Recommendations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alessandro Petruzzelli
  - Cataldo Musto
  - admin
  - Ivan Rinaldi
  - Marco de Gemmis
  - Pasquale Lops
  - Giovanni Semeraro
  

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-10-08T00:00:00Z'
doi: 'https://doi.org/10.1145/3640457.3688137'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-08T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 18th ACM Conference on Recommender Systems*
publication_short: In *RecSys24*

abstract: This paper presents a strategy for explainable cross-domain recommendations (CDR) using large language models (LLMs). CDR is challenging due to data sparsity, as it requires extensive labeled data across both source and target domains, which is hard to collect. Our approach leverages the knowledge in LLMs to bridge these domains and provide personalized recommendations. We developed a pipeline to (a) instruct an LLM for CDR tasks, (b) design a personalized prompt based on user preferences and target items, and (c) generate recommendations and explanations using zero-shot and one-shot settings. Experimental results show our method outperforms state-of-the-art baselines.

# Summary. An optional shortened abstract.
summary: This paper presents a strategy for explainable cross-domain recommendations (CDR) using large language models (LLMs). CDR is challenging due to data sparsity, as it requires extensive labeled data across both source and target domains, which is hard to collect. Our approach leverages the knowledge in LLMs to bridge these domains and provide personalized recommendations.

tags:
  - Cross-domain Recommendations
  - Instruction Tuning
  - Large Language Models
  - Recommender Systems

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3640457.3688137'
url_code: 'https://github.com/petruzzellialessandro/RecSys_2024_CDR_LLM'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Petruzzelli et al**](https://dl.acm.org/doi/10.1145/3640457.3688137)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This sutdy explores how to improve cross-domain recommendation systems using large language models (LLMs). Cross-domain recommendation systems (CDRs) help users receive personalized recommendations across different areas, such as suggesting books based on a user’s movie preferences. However, these systems often suffer from data sparsity, making it difficult to gather enough labeled data from both domains (source and target) to train the models effectively.

To address this, we propose a strategy that uses the knowledge encoded in LLMs to bridge the gap between different domains. The key innovation is to prompt LLMs by providing user preferences from one domain (e.g., movie ratings) and applying that knowledge to recommend items in another domain (e.g., books). The paper outlines a workflow that involves fine-tuning the LLM through instruction-based learning and carefully designed prompts that generate recommendations along with natural language explanations.

The experimental results show that this approach outperforms other state-of-the-art models, both in zero-shot (no prior domain-specific training) and one-shot settings (limited training), making it a promising direction for more explainable AI-driven recommendation systems​.