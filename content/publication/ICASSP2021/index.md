---
title: Attack on practical speaker verification system using universal
  adversarial perturbations

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weiyi Zhang
  - admin
  - Le Liu
  - Jianmin Li
  - Xingliang Cheng
  - Thomas Fang Zheng
  - Xiaolin Hu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-06-01T00:00:00.000Z'
# doi: '2105.09022'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-06-01T00:00:00.000Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ICASSP 2021-2021 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
publication_short: ICASSP 2021

abstract: In authentication scenarios, applications of practical speaker
  verification systems usually require a person to read a dynamic authentication
  text. Previous studies played an audio adversarial example as a digital signal
  to perform physical attacks, which would be easily rejected by audio replay
  detection modules. This work shows that by playing our crafted adversarial
  perturbation as a separate source when the adversary is speaking, the the
  practical speaker verification system will misjudge the adversary as a target
  speaker. A two-step algorithm is proposed to optimize the universal
  adversarial perturbation to be text-independent and has little effect on
  authentication text recognition. We also estimated room impulse response (RIR)
  in the algorithm which allowed the perturbation to be effective after being
  played over the air. In the physical experiment, we achieved targeted attacks
  with a success rate of 100%, while the word error rate (WER) on speech
  recognition only increased by 3.55%. And recorded audio could pass replay
  detection for the live person speaking.

# Summary. An optional shortened abstract.
summary: This paper demonstrates a physical-world attack on speaker verification systems by playing a carefully crafted, text-independent adversarial perturbation alongside the adversary's speech, achieving a 100% success rate in targeted attacks with minimal impact on speech recognition.

tags:
  - Adversarial Attacks and Defenses
  - Speech and Audio AI

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2105.09022'
url_code: 'https://github.com/zhang-wy15/Attack_practical_asv'
url_dataset: 'https://www.openslr.org/12'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/zhang-wy15/Attack_practical_asv'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Schematic diagram of attacking the PSV system'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - ""

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
