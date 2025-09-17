---
title: "Blog"
type: landing
slug: "blog"
design:
  spacing: "3rem"

sections:
  # Encabezado simple
  - block: hero
    content:
      title: "Notas del Blog"
      text: "Historias, aprendizajes y recursos de MetaDocencia."
    design:
      spacing:
        padding: ["0.5rem", 0, "0.5rem", 0]
        margin: [0, 0, 0, 0]
      background:
        color: ""
      text_color_light: false

  # Listado tipo tarjetas (2 columnas), con búsqueda y tags
  - block: collection
    id: blog-list
    content:
      search:
        enabled: true
        placeholder: "Buscar notas…"
      # Filtra por secciones donde tengas las notas (ajusta según tu repo)
      filters:
        folders: ["post", "blog"]   # si tus posts están en content/post/ o content/blog/
      count: 24                      # cuántas mostrar
      sort_by: "date"
      sort_ascending: false
      page_size: 12                  # paginación
      view: "card"                   # muestra tarjetas
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
      css_class: "md:columns-2"
      card:
        css_class: "hb-card-article"
