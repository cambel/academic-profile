---
title: "Hybrid Trajectory and Force Learning of Complex Assembly Tasks: A Combined Learning Framework"
authors:
- Yan Wang
- admin
- Weiwei Wan
- Kensuke Harada
date: "2021-04-16T00:00:00Z"
doi: "https://doi.org/10.1109/ACCESS.2021.3073711"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: "IEEE Access 2021"

abstract: Complex assembly tasks involve nonlinear and low-clearance insertion trajectories with varying contact forces at different stages. For a robot to solve these tasks, it requires a precise and adaptive controller which conventional force control methods cannot provide. Imitation learning is a promising method for learning controllers that can solve the nonlinear trajectories from human demonstrations without needing to explicitly program them into the robot. However, the force profiles obtain from human demonstration via tele-operation tend to be sub-optimal for complex assembly tasks, thus it is undesirable to imitate such force profiles. Reinforcement learning learns adaptive control policies through interactions with the environment but struggles with low sample efficiency and equipment tear and wear in the physical world. To address these problems, we present a combined learning-based framework to solve complex robotic assembly tasks from human demonstrations via hybrid trajectory learning and force learning. The main contribution of this work is the development of a framework that combines imitation learning, to learn the nominal motion trajectory, with a reinforcement learning-based force control scheme to learn an optimal force control policy, which can satisfy the nominal trajectory while adapting to the force requirement of the assembly task. To further improve the imitation learning part, we develop a hierarchical architecture, following the idea of goal-conditioned imitation learning, to generate the trajectory learning policy on the skill level offline. Through experimental validations, we corroborate that the proposed learning-based framework can generate high-quality trajectories and find suitable force control policies which adapt to the tasks’ force requirements more efficiently.

# Summary. An optional shortened abstract.
summary: Combining imitation learning with reinforcement learning to solve complex robotic assembly tasks. 

tags:
- Learning by Demonstration
- Imitation Learning
- Reinforcement Learning
- Force Control
featured: true

links:
url_pdf: https://ieeexplore.ieee.org/document/9406007
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
