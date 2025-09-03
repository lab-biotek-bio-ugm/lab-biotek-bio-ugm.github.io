---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Biotech Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Biotechnology Laboratory** at Faculty of Biology, Universitas Gadjah Mada, <span style="font-size: smaller;">supports teaching and research in molecular biology, plant tissue culture, microalgae engineering, and genetic engineering.</span>

        <br>
        <span style="font-size: smaller;">
        Equipped with modern instruments, it provides facilities for developing technical competencies, applying scientific methods, and fostering innovations in biotechnology.
        </span>
  
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'
  
  - block: tag_cloud
    content:
      title: Popular Topics
      subtitle:
      text:
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 20
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0
---

