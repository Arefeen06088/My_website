---
title: 'GlySim: Modeling and Simulating Glycemic Response for Behavioral Lifestyle Interventions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hassan Ghasemzadeh

# Author notes (optional)
author_notes:

date: '2023-07-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE-EMBS International Conference on Biomedical and Health Informatics (BHI’23)
publication_short: 

abstract: Effective prevention and management of diabetes relies on maintaining a normal blood glucose level, thus avoiding abnormal events such as hyperglycemia and hypoglycemia. Predicting anomalous events beforehand can potentially help patients and caregivers intervene to prevent such events through modifiable behaviors such as exercise, diet, and medication. Although Continuous Glucose Monitor (CGM) sensors have been used to monitor and forecast blood glucose level, current research lacks a computational approach that recommends a behavioral intervention to bring the glucose level to a normal range. To address this shortcoming, we present GlySim, a CGM simulator that uses multimodal data to not only forecast future glucose readings but also enable a user to examine the impacts of behavior change on glucose response in advance. GlySim creates opportunities for change in food consumption, medication, and physical activity to avoid dysglycemia by pinpointing factors that cause anomalous events using Grad-CAM (Gradient-weighted Class Activation Mapping) and allowing users to observe how adjusting a behavioral factor changes glucose trajectories. We validate GlySim on a dataset of 10 patients with type 1 diabetes and achieve an overall mean absolute error (MAE) as low as 16.5 mg/dl in simulating glycemic response. Furthermore, Glysim detects hyperglycemic events with 0.89 average precision.

# Summary. An optional shortened abstract.
summary: GlySim accurately forecasts future blood glucose level, intervenes by identifying the factor contributing most towards blood glucose spike and suggests optimal behavioral change to avoid abnormality.

tags:
  - AI driven intervention

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1txoD1VZHk1xLz5t7X6ICdOqvrUnsCNV7/view'
url_code: 'https://github.com/Arefeen06088/GlySim'
url_dataset: 'https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7881904/'
url_poster: 'https://www.linkedin.com/posts/asiful-arefeen-514208aa_ieee-bhi23-pittsburgh-activity-7121266348806062082-EnJV?utm_source=share&utm_medium=member_desktop'
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
