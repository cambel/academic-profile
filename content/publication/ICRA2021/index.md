---
title: "Robotic Imitation of Human Assembly Skills Using Hybrid Trajectory and Force Learning"
authors:
- Yan Wang
- admin
- Weiwei Wan
- Kensuke Harada
date: "2021-04-01T00:00:00Z"
# doi: "https://doi.org/10.1109/LRA.2020.3010739"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Robotics and Automation"
publication_short: "ICRA 2021"

abstract: Robotic assembly tasks involve complex and low-clearance insertion trajectories with varying contact forces at different stages. While the nominal motion trajectory can be easily obtained from human demonstrations through kinesthetic teaching, teleoperation, simulation, among other methods, the force profile is harder to obtain especially when a real robot is unavailable. It is difficult to obtain a realistic force profile in simulation even with physics engines. Such simulated force profiles tend to be unsuitable for the actual robotic assembly due to the reality gap and uncertainty in the assembly process. To address this problem, we present a combined learning-based framework to imitate human assembly skills through hybrid trajectory learning and force learning. The main contribution of this work is the development of a framework that combines hierarchical imitation learning, to learn the nominal motion trajectory, with a reinforcement learning-based force control scheme to learn an optimal force control policy, that can satisfy the nominal trajectory while adapting to the force requirement of the assembly task. To further improve the imitation learning part, we develop a hierarchical architecture, following the idea of goal-conditioned imitation learning, to generate the trajectory learning policy on the \textit{skill} level offline. Through experimental validations, we corroborate that the proposed learning-based framework is robust to uncertainty in the assembly task, can generate high-quality trajectories, and can find suitable force control policies, which adapt to the task's force requirements more efficiently.

# Summary. An optional shortened abstract.
# summary: A learning-based force control framework for position-controlled robots

tags:
- Learning by Demonstration
- Imitation Learning
- Reinforcement Learning
- Force Control
featured: true

links:
- name: "preprint"
  url: https://arxiv.org/abs/2103.05912
# url_pdf: https://ieeexplore.ieee.org/document/9145608
# url_code: mailto:cristianbehe@gmail.com
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''

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
