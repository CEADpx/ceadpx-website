---
# Leave the homepage title empty to use the site title
title:
date: 2025-01-01
type: landing

sections:
  - block: hero
    content:
      title: |
        Computational Engineering Analysis and Design (CEAD) Lab
      image:
        filename: welcome.png
      text: |
        <br>
        
        The CEAD Lab at South Dakota Mines, created and led by PI Prashant K. Jha, aims to address challenging problems of modeling, analysis, and design in engineering fields. Broadly, we are interested in fracture and failure in materials, functional soft materials, and granular materials. 
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <br> We are actively seeking enthusiastic undergraduate and graduate students interested in computational mechanics and applying advanced numerical and machine learning-based methods to problems in fracture mechanics, functional soft materials, and granular materials.
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: welcome.png
          filters:
            brightness: 0.8
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
