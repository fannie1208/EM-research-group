---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

design:
  columns: '1'
  css_style: 
  css_class:
---

<div class="sponsor-container">
  <span>Sponsor</span>
  <div class="images" style="display: grid;
  grid-template-columns: auto 1fr; 
  align-items: center;">
    {{< figure src="logo1.jpg" height="150">}}
    {{< figure src="logo2.jpg" height="150">}}
  </div>
</div>