---
# Leave the homepage title empty to use the site title
title:
date: 2023-4-27
type: landing

sections:
  - block: hero
    id: welcome
    content:
      title: Xie Lab
      image:
        filename: welcome.png
      text: |-
        **Electron Microscope and Extreme Matter (EM) lab** aims to develop and deploy advanced electron miscopy techniques to address pending challenges in engineering systems that involve matters in extreme conditions.

    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - news
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: collection
    id: publication
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: compact
---
