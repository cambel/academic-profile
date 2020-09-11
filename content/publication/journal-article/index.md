---
title: "Learning Force Control for Contact-rich Manipulation Tasks with Rigid Position-controlled Robots"
authors:
- admin
- Damien Petit
- Ixchel Georgina Ramirez-Alpizar
- Takayuki Nishi
- Shinichi Kikuchi
- Takamitsu Matsubara
- Kensuke Harada
date: "2020-07-21T00:00:00Z"
doi: "https://doi.org/10.1109/LRA.2020.3010739"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Robotics and Automation Letters"
publication_short: "IROS RA-L 2020"

abstract: Reinforcement Learning (RL) methods have been proven successful in solving manipulation tasks autonomously. However, RL is still not widely adopted on real robotic systems because working with real hardware entails additional challenges, especially when using rigid position-controlled manipulators. These challenges include the need for a robust controller to avoid undesired behavior, that risk damaging the robot and its environment, and constant supervision from a human operator. The main contributions of this work are, first, we proposed a learning-based force control framework combining RL techniques with traditional force control. Within said control scheme, we implemented two different conventional approaches to achieve force control with position-controlled robots; one is a modified parallel position/force control, and the other is an admittance control. Secondly, we empirically study both control schemes when used as the action space of the RL agent. Thirdly, we developed a fail-safe mechanism for safely training an RL agent on manipulation tasks using a real rigid robot manipulator. The proposed methods are validated both on simulation and a real robot with an UR3 e-series robotic arm.

# Summary. An optional shortened abstract.
summary: Code available on request

tags:
- Reinforcement Learning
- Force Control
- Peg-in-hole
featured: true

links:
- name: "preprint"
  url: "https://arxiv.org/abs/2003.00628"
url_pdf: https://ieeexplore.ieee.org/document/9145608
# url_code: mailto:cristianbehe@gmail.com
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: hhttps://www.youtube.com/watch?v=4wdIhQxD6cA&t=14s

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'System overview'
#   focal_point: ""
#   preview_only: false

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
# slides: example
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
