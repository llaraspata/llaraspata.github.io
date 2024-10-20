---
title: 'Enhancing human capital management through GPT-driven questionnaire generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Fabio Cardilli
  - Giovanna Castellano
  - Gennaro Vessio
  

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-10-18T00:00:00Z'
#doi: 'https://doi.org/10.1145/3640457.3688137'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 8th workshop on Natural Language for Artificial Intelligence*
publication_short: In *NL4AI 2024*

abstract: The study addresses a gap in the literature regarding AI-generated surveys for Human Capital Management. A novel dataset of HR questions was developed, and the models were evaluated using different techniques, such as zero-shot and one-shot prompting, to assess their ability to generate diverse, semantically accurate, and instruction-aligned questions. The evaluation focused on several aspects, that is syntactic and lexical diversity, alignment with human-authored questions, and serendipity.

# Summary. An optional shortened abstract.
summary: The study addresses a gap in the literature regarding AI-generated surveys for Human Capital Management. A novel dataset of HR questions was developed, and the models were evaluated using different techniques, such as zero-shot and one-shot prompting, to assess their ability to generate diverse, semantically accurate, and instruction-aligned questions.

tags:
  - Questionnaire Generation
  - Human Capital Management
  - Generative AI
  - Large Language Models
  - Prompt Engineering

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/llaraspata/HRMQuestionnaireGenerationUsingLLM'

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

Survey questionnaires capture employee insights and guide strategic decision-making in Human Capital Management. This study explores the application of the GPT-3.5-Turbo and GPT-4-Turbo models for the automated generation of HR-related questionnaires, addressing a significant gap in the literature. 

We developed a novel dataset of HR survey questions and evaluated the models’ performance using different task configurations, including zero-shot and one-shot prompting with various hyperparameter settings. The generated questionnaires were assessed for instruction alignment, syntactic and lexical diversity, semantic similarity to human-authored questions, and topic diversity, or serendipity. In collaboration with Talentia Software, we additionally examined the indistinguishability of AI-generated content from human-created counterparts. 

Results indicate that both models produce questionnaires with high serendipity and intra-questionnaire diversity. However, the indistinguishability test revealed that human evaluators could still distinguish AI-generated content, particularly noting differences in language style and answer variability. These findings underscore the potential of GPT-driven tools in automating questionnaire generation while highlighting the need for further refinement to achieve more human-like outputs.