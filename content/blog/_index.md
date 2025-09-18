---
title: "Blog"
type: landing
slug: "blog"

sections:
  # Título simple (sin hero)
  - block: markdown
    content:
      text: |
        # Blog
    design:
      css_class: "mb-2"

  # Listado de notas
  - block: collection
    content:
      # Dejamos que apunte a la sección actual (blog) sin filtros raros
      count: 24
      page_size: 12
      sort_by: "date"
      sort_ascending: false

      # UI de las tarjetas
      show_image: true
      show_date: true
      show_read_time: true
      show_authors: true
      show_tags: true
      show_excerpt: true
      link_to_item: true

      # Si tenés posts en `content/post/` además de `content/blog/` y querés incluirlos:
      # filters:
      #   folders: ["blog", "post"]

    design:
      columns: 2
      card:
        css_class: "shadow-sm hover:shadow-md transition"
---
