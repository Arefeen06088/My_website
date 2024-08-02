---
title: "Inter-Beat Interval Estimation with Tiramisu Model: A Novel Approach with Reduced Error"
authors:
- admin
- Ali Akbari
- Seyed-Iman Mirzadeh
- Roozbeh Jafari
- Behrooz A. Shirazi
- Hassan Ghasemzadeh
author_notes:
- ""

date: "2023-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Computing for Healthcare"
publication_short: "In *ACM Health*"

abstract: Inter-beat interval (IBI) measurement enables estimation of heart-tare variability (HRV) which, in turns, can provide early indication of potential cardiovascular diseases (CVDs). However, extracting IBIs from noisy signals is challenging since the morphology of the signal gets distorted in the presence of noise. Electrocardiogram (ECG) of a person in heavy motion is highly corrupted with noise, known as motion-artifact, and IBI extracted from it is inaccurate. As a part of remote health monitoring and wearable system development, denoising ECG signals and estimating IBIs correctly from them have become an emerging topic among signal-processing researchers. Apart from conventional methods, deep-learning techniques have been successfully used in signal denoising recently, and diagnosis process has become easier, leading to accuracy levels that were previously unachievable. We propose a deep-learning approach leveraging tiramisu autoencoder model to suppress motion-artifact noise and make the R-peaks of the ECG signal prominent even in the presence of high-intensity motion. After denoising, IBIs are estimated more accurately expediting diagnosis tasks. Results illustrate that our method enables IBI estimation from noisy ECG signals with SNR up to -30dB with average root mean square error (RMSE) of 13 milliseconds for estimated IBIs. At this noise level, our error percentage remains below 8% and outperforms other state of the art techniques.

# Summary. An optional shortened abstract.
summary: With a Tiramisu model, we have been able to denoise ECG signals buried under motion noise and estimate inter-beat-intervals (IBI) accurately.

tags:
- Signal Denoising
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://drive.google.com/file/d/1spJ4IiTO6g6grsUGvaj5YHEiQkrPI8uf/view
url_code: 'https://github.com/Arefeen06088/IBI_Tiramisu'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
