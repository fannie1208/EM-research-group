---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: pages # See https://wowchemy.com/docs/page-builder/
headless: true # This file represents a page section.
weight: 20 # Order that this section will appear.
title: <span style="font-size:25px">RECENT PUBLICATION</span>

content:
  count: 1
  # Filter on criteria
  filters:
    folders:
      - publication
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
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
  # Add custom styles
  view: compact
---