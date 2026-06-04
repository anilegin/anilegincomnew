---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-03-08
type: landing

design:
  spacing: "5rem"

sections:
  - block: resume-biography-3
    id: about
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/cv-anil-egin-20-05-2026.pdf
    design:
      css_class: dark
      background:
        color: '#2a3544'

  - block: markdown
    id: highlights
    content:
      title: Highlights
      text: |-
        - **Feb 2026** — Research assistant at [VRAI Lab](https://vrai.dii.univpm.it/): multi-view video synchronization and applied vision for color analysis.
        - **Oct 2025** — Oral at CV4BIOM ([ICCV 2025](publication/iccv2025/)) on [talking-head video anonymization](publication/iccv2025/) (INRIA STARS).
        - **2024–2025** — AI research intern at [INRIA STARS](https://team.inria.fr/stars/): video anonymization, facial treatment GNNs, and StyleGAN3 identity control.
        - **Jun–Dec 2023** — Business Intelligence Engineer Intern at [Amazon](https://www.amazon.it/).
        - **MSc** — Artificial Intelligence and Robotics at [Sapienza University](https://www.uniroma1.it/).
        - **BSc** — Computer Science and Artificial Intelligence at [Bocconi University](https://www.unibocconi.it/).
    design:
      columns: '1'

  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      count: 0
      filters:
        folders:
          - publication
    design:
      view: article-grid
      columns: 1

  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: true

  - block: markdown
    id: projects
    content:
      title: Projects
      subtitle: ''
      text: |-
        Source code and implementations are on **[GitHub @anilegin](https://github.com/anilegin)**. Selected work:

        - **[AnonNET](https://github.com/anilegin/AnonNET)** — Talking-head video anonymization with diffusion inpainting, ControlNet, and landmark-free motion transfer.
        - **[TurtleBot3-Navigation-Metrics](https://github.com/anilegin/TurtleBot3-Navigation-Metrics)** — Adaptive ROS2 / Nav2 navigation with LSTM-based risk assessment and dynamic planner tuning.
        - **[semantic-retrieval-transformers](https://github.com/anilegin/semantic-retrieval-transformers)** — BGE/MiniLM retrieval with hard-negative mining and cross-encoder re-ranking.
        - **[visualsync](https://github.com/anilegin/visualsync)** — Multi-view video synchronization (VRAI Lab).

        Browse all repositories on [github.com/anilegin](https://github.com/anilegin).
    design:
      columns: '1'

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        Reach out for research collaboration, internships, or just to connect.
    design:
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-button-list
    content:
      buttons:
        - text: E-mail
          icon: at-symbol
          url: mailto:anilegin@gmail.com
        - text: GitHub
          icon: brands/github
          url: https://github.com/anilegin
        - text: LinkedIn
          icon: brands/linkedin
          url: https://www.linkedin.com/in/anilegin/
        - text: Scholar
          icon: academicons/google-scholar
          url: https://scholar.google.com/citations?user=7ONZPpoAAAAJ/
    design:
      columns: 2
---
