---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: News
      count: 5
      text: |-
        - **2024/07**, Sijia received the IEEE Computer Society Student Travel Grants to support her oral presentation at QCE24.
        - **2024/06**, Our paper on Distributed quantum ML-based stability assessment is accepted by 2024 IEEE International Conference on Quantum Computing and Engineering (QCE24).
        - **2024/03**, Three papers are accepted by 2024 IEEE PESGM on Learning-enabled runtime reachable dynamics, [Stochastic reachable dynamics](https://drive.google.com/file/d/1ReS7-4GYKV3YtYXAS4XCWtxg1swa8e9h/view), and [Adversarial-resilient quantum ML](https://drive.google.com/file/d/1Ra7rCYsL5ep-v9kdDYp8q8LKPzd_YN7W/view).
        - **2024/01**, Our paper on [Neural dynamic state estimation](https://ieeexplore.ieee.org/abstract/document/10457950) is accepted by IEEE Transactions on Industry Applications.
        - **2023/10**, Our paper on [Neural dynamic equivalencing](https://arxiv.org/pdf/2309.16950) is selected as the Top 5 in the 2023 CIGRE Next Generation Network (NGN) Paper Competition.
        - [PAST NEWS](/news/)
    design:
      columns: '2'
  - block: portfolio
    id: research
    content:
      title: Research Interests
      filters:
        folders:
          - research
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
    design:
      columns: '2'
      view: compact
      flip_alt_rows: false
  
  - block: collection
    id: publications
    content:
      title: Publications
      count: 10
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      # view: community/citation_custom
      view: community/publication_list_custom
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |-
        - **ESE 352 - Electromechanical Energy Converters** (Undergraduate): Fall 2024, Fall 2023, Fall 2022.
        - **EEO 425 - Electric Machinery and Energy Conversion** (Online): Fall 2024, Fall 2023, Fall 2022.
        - **ESE 562 - AI-Driven Smart Grids** (Graduate): Fall 2024.
        - **ESE 586 - Microgrids** (Graduate): Fall 2023, Fall 2022.
    design:
      columns: '2'
  - block: markdown
    id: team
    content:
      title: Mentoring
      text: |-
        - **Yao Xiao** (PhD student, Fall 2024 - )
        - **Xuguo Fu** (PhD student, Fall 2023 - )
        - **Sijia Yu** (PhD student, Spring 2023 - )
        - **Qing Shen** (Co-advised PhD student, Fall 2022 - )
        - **Trisha Sabadra** (High school student, Summer 2024)
        - **Asha Boyapati**  (High school student, Summer 2024)
    design:
      columns: '2'
  - block: markdown
    id: awards
    content:
      title: Awards
      text: |-
        - **2023**,  Young Academic Inventor’s Award from the National Academy of Inventors (NAI) Stony Brook University Chapter, recognized for her ”fundamental work in quantum computing techniques for large-scale power system problems”
        - **2021**, Outstanding Reviewer for IEEE Transactions on Power Systems
        - **2014**, Outstanding Graduate of Tsinghua University (1.5%) 
        - **2014**, Outstanding Graduate of Beijing
        - **2014**, Outstanding Thesis Award, Tsinghua University
    design:
      columns: '2'
---
