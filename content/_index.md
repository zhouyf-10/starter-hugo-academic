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
      text: |-
        - **2023/08**, Our paper on [learning-based, safety and stability-certified microgrid control](https://ieeexplore.ieee.org/abstract/document/10233047) is accepted by IEEE Transactions on Smart Grid.
        - **2023/03**, Our paper on [noise-intermediate-scale quantum EMTP](https://ieeexplore.ieee.org/abstract/document/9769895) is published by IEEE Transactions on Power Systems.
        - **2023/03**, Our paper on [noise-resilient quantum power flow](https://ieeexplore.ieee.org/abstract/document/10144277) is accepted by iEnergy.
        - **2023/01**, Our paper on [quantum machine learning-based transient stability assessment](https://ieeexplore.ieee.org/abstract/document/9737359) is published by IEEE Transactions on Power Systems.
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
        - ESE 352 - Electromechanical Energy Converters (Undergraduate): Fall 2024, Fall 2023, Fall 2022.
        - EEO 425 - Electric Machinery and Energy Conversion (Online): Fall 2024, Fall 2023, Fall 2022.
        - ESE 562: AI-Driven Smart Grids (Graduate): Fall 2024.
        - ESE 586: Microgrids (Graduate): Fall 2024, Fall 2023, Fall 2022, Spring 2022, Spring 2021.
    design:
      columns: '2'
  - block: markdown
    id: students
    content:
      title: Mentoring
      text: |-
    - Yao Xiao (Fall 2024-)
    - Xuguo Fu (Fall 2023-)
    - Sijia Yu (Spring 2023-)
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
