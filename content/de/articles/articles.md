---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featured

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Veröffentlichte Artikel
subtitle: ""

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Filter on criteria
  filters:
    author: ""
    category: ""
    publication_type: "2"
    tag: ""
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 1
---

Der {{< icon name="file-pdf" pack="fas">}}PDF Button führt entweder zu Seite des Herausgebers (für{{< icon name="open-access" pack="ai">}}Open Access Artikel) oder zu einem Repositorium mit der Autorenversion (für{{< icon name="closed-access" pack="ai">}}Closed Access Artikel).