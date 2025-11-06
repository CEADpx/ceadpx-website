---
# Leave the homepage title empty to use the site title
title:
date: 2025-01-01
type: landing

sections:
  - block: hero
    content:
      image:
        filename: welcome.png
      text: |
        The **Computational Engineering Analysis & Design (CEAD) Lab** within Leslie A. Rose Department of Mechanical Engineering at South Dakota Mines, led by Dr. Prashant K. Jha, addresses complex challenges in modeling, simulation, and design across engineering disciplines. Our work spans fracture and failure mechanics, functional soft materials such as magnetic and dielectric polymers, and the mechanics of granular and heterogeneous materials. We also develop neural operators and machine learning methods for scientific computing, with a focus on controlling and quantifying approximation errors. By combining advanced computational methods with innovative design strategies, we aim to deepen understanding of material behavior and deliver solutions for demanding real-world applications.
  - block: markdown
    content:
      title: Focus areas
      text: |
        **Fracture Mechanics:** Fracture and fatigue in complex materials, e.g., soft composites, functional materials
        
        **Granular Media Mechanics:** High and multi-fidelity mechanics simulation of particles under significant loading

        **Neural Networks/Operators for Scientific Computing:** Application of neural operators as surrogate of PDE-based problems and error estimation and control of neural operator surrogates

        **Analysis and Design of Smart Materials:** Microstructure-property relation and design of novel materials such as magnetically and electrically active soft materials

        ![](focus_areas.png)

    design:
      columns: '1'
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        We are actively seeking enthusiastic undergraduate and graduate students interested in computational mechanics and applying advanced numerical and machine learning-based methods to problems in fracture mechanics, functional soft materials, and granular materials.
        {{% cta cta_link="./contact/" cta_text="Interested candidates should email me here!" %}}
    design:
      columns: '1'

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     # background:
  #     #   image: 
  #     #     filename: icon.png
  #     #     filters:
  #     #       brightness: 0.8
  #     #     parallax: false
  #     #     position: center
  #     #     size: cover
  #     #     text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
