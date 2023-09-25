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
        - **2022/06**, Our paper APF is accepted by IEEE Transactions on Power Systems.
        - **2022/05**, Our paper QSLR is accepted by IEEE Transactions on Power Systems.
        - **2022/05**, Our paper NISQ-QEMTP is accepted by IEEE Transactions on Power Systems.
        - **2022/05**, Our paper QTSA is accepted by IEEE Transactions on Power Systems.
        - **2022/02**, Our paper NeuEMTP is accepted by PESGM 2022.
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
  - block: portfolio
    id: presentations
    content:
      title: Presentations
      filters:
        folders:
          - presentations
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
    design:
      columns: '2'
      view: 5
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
    id: awards
    content:
      title: Awards
      text: |-
        - **2023**, 2023 Young Academic Inventor’s Award from the National Academy of Inventors
(NAI) Stony Brook University Chapter, recognized for her ”fundamental work in quantum computing techniques
for large-scale power system problems”
        - **2021**, Outstanding Reviewer for IEEE Transactions on Power Systems
        - **2014**, Outstanding Graduate of Tsinghua University (1.5%) (1/4)
        - **2014**, Outstanding Graduate of Beijing
        - **2014**, Outstanding Thesis Award, Tsinghua University
    design:
      columns: '2'
---
