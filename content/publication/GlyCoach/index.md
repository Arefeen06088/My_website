---
title: "Designing User-Centric Behavioral Interventions to Prevent Dysglycemia with
Novel Counterfactual Explanations"
authors:
- admin
- Hassan Ghasemzadeh
date: "2023-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "GlyCoach"

abstract: Maintaining normal blood glucose levels through lifestyle behaviors is central to maintaining health and preventing disease. Frequent exposure to dysglycemia (i.e., abnormal glucose events such as hyperlycemia and hypoglycemia) leads to chronic complications including diabetes, kidney disease and need for dialysis, myocardial infarction, stroke, amputation, and death. Therefore, a tool capable of predicting dysglycemia and offering users actionable feedback about how to make changes in their diet, exercise, and medication to prevent abnormal glycemic events could have significant societal impacts. Counterfactual explanations can provide insights into why a model made a particular prediction by generating hypothetical instances that are similar to the original input but lead to a different prediction outcome. Therefore, counterfactuals can be viewed as a means to design AI-driven health interventions to prevent adverse health outcomes such as dysglycemia. In this paper, we design GlyCoach, a framework for generating counterfactual explanations for glucose control. Leveraging insights from adversarial learning, GlyCoach characterizes the decision boundary for high-dimensional health data and performs a grid search to generate actionable interventions. GlyCoach is unique in integrating prior knowledge about user preferences of plausible explanations into the process of counterfactual generation. We evaluate GlyCoach extensively using two real-world datasets and external simulators from prior studies that predict glucose response. GlyCoach achieves 87\% sensitivity in the simulation-aided validation, surpassing the state-of-the-art techniques for generating counterfactual explanations by at least 10%. Besides, counterfactuals from GlyCoach exhibit a 32% improved normalized distance compared to previous research.

# Summary. An optional shortened abstract.
summary: GlyCoach presents a novel approach to charaterize the decision boundary of a model and leverage it to generate counterfactual expalantions reflecting user preferences.

tags:
- Counterfactual Explanations

featured: true

links:
- name: Custom Link
  url: https://arxiv.org/abs/2310.01684
url_pdf: https://arxiv.org/pdf/2310.01684
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7881904/'
url_poster: '#'
url_project: ''
url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=Kp-MuHiHYPE'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Metabollic Health

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

