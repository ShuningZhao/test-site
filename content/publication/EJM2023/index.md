---
title: Predicting crowdfunding success with visuals and speech in video ads and
  text ads
authors:
  - Osamah M Al-Qershi
  - Junbum Kwon
  - admin
  - Zhaokun Li
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-08-07T14:08:36.071Z"
doi: "https://doi.org/10.1108/EJM-01-2020-0029"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: European Journal of Marketing
publication_short: "EJM 2023"

abstract: >-
  This study investigates the impact of various video and textual content features on the predictive accuracy of crowdfunding campaign success.  Using a dataset of 15,195 Kickstarter campaigns, we compare the performance of logistic regression (LR) with tree-based ensemble methods, including eXtreme Gradient Boosting (XGBoost) and heterogeneous ensembles (XGBoost + LR).  Contrary to previous findings, XGBoost significantly outperforms LR (82% vs. 69% accuracy).  Feature importance analysis reveals that human-centric visual elements (e.g., founders) are more influential than product-focused visuals.  Linguistically, words related to experience and perception, as well as a future-oriented time perspective, are stronger predictors of success than cognitive or past/present-focused language.  Complementary cues across modalities, such as speech aids reinforcing visual content, and non-content features like positive tone, also contribute significantly.  These findings provide practical guidance for campaign creators to optimize their video and text ad content, emphasizing the importance of human presence, experiential language, and cross-modal reinforcement, while also cautioning against overly complex ensemble models without proper validation. The research expands on previous approaches. By not reducing content feature dimensions.

# Summary. An optional shortened abstract.
summary: This research shows that using advanced prediction models, like XGBoost, with many content features from video and text ads (focusing on human presence, experiential language, and future orientation) significantly improves the accuracy of predicting Kickstarter campaign success.
tags:
  - Crowdfunding
  - Video Analysis
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://doi.org/10.1108/EJM-01-2020-0029'
url_code: ''
url_dataset: 'https://www.kickstarter.com/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Kickstarter**](https://www.kickstarter.com/)'
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
slides: ''
---

### Purpose
For the case of many content features, This paper aims to investigate which content features in video and text ads more contribute to accurately predicting the success of crowdfunding by comparing prediction models.

### Design/methodology/approach
With 1,368 features extracted from 15,195 Kickstarter campaigns in the USA, the authors compare base models such as logistic regression (LR) with tree-based homogeneous ensembles such as eXtreme gradient boosting (XGBoost) and heterogeneous ensembles such as XGBoost + LR.

### Findings
XGBoost shows higher prediction accuracy than LR (82% vs 69%), in contrast to the findings of a previous relevant study. Regarding important content features, humans (e.g. founders) are more important than visual objects (e.g. products). In both spoken and written language, words related to experience (e.g. eat) or perception (e.g. hear) are more important than cognitive (e.g. causation) words. In addition, a focus on the future is more important than a present or past time orientation. Speech aids (see and compare) to complement visual content are also effective and positive tone matters in speech.

### Research limitations/implications
This research makes theoretical contributions by finding more important visuals (human) and language features (experience, perception and future time). Also, in a multimodal context, complementary cues (e.g. speech aids) across different modalities help. Furthermore, the noncontent parts of speech such as positive “tone” or pace of speech are important.

### Practical implications
Founders are encouraged to assess and revise the content of their video or text ads as well as their basic campaign features (e.g. goal, duration and reward) before they launch their campaigns. Next, overly complex ensembles may suffer from overfitting problems. In practice, model validation using unseen data is recommended.

### Originality/value
Rather than reducing the number of content feature dimensions (Kaminski and Hopp, 2020), by enabling advanced prediction models to accommodate many contents features, prediction accuracy rises substantially.