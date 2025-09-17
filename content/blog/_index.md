---
title: "Blog"
type: landing
slug: "blog"
design:
  spacing: "3rem"

sections:

  # Listado de posts en tarjetas
  - block: collection
    id: blog-list
    content:
      search:
        enabled: true
        placeholder: "Buscar notas…"
      # Ajusta según dónde tengas los posts
      filters:
        folders: ["post", "blog"]
      count: 24
      sort_by: "date"
      sort_ascending: false
      page_size: 12
      view: "card"
      show_image: true
      show_date: true
      show_read_time: true
      show_authors: true
      show_tags: true
      show_excerpt: true
      link_to_item: true
      empty_text: "Pronto publicaremos más notas."
    design:
      columns: 2
      card:
        css_class: "hb-card-article"
---
