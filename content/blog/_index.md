---
title: "Blog"
type: landing
slug: "blog"

design:
  spacing: "2rem"

sections:
  # Título simple (sin hero)
  - block: cta-card
    content:
      title: "Blog"
      text: ""
    design:
      card:
        css_class: "bg-transparent p-0 text-left"

  # Listado horizontal de notas
  - block: collection-horizontal
    id: blog-list
    content:
      filters:
        folders: ["post", "blog"]   # ajustá si tus posts están en otra sección
      count: 24
      sort_by: "date"
      sort_ascending: false
      show_image: true
      show_date: true
      show_authors: true
      show_tags: true
      show_excerpt: true
      page_size: 0                  # 0 = sin paginación en este bloque
      empty_text: "Pronto publicaremos más notas."
    design:
      css_class: "blog-horizontal"
---
