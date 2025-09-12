---
title: "Home"
type: landing

# ↓ reduce el espacio vertical global entre secciones
design:
  spacing: "3rem"

sections:
  - block: hero
    content:
      title: "Quiénes somos"
      text: "MetaDocencia es una organización sin fines de lucro fundada en 2020. Nuestra comunidad construye capacidades científicas locales para transformar la ciencia global. Hacemos crecer la ciencia en red, desde América Latina hacia el mundo."
      primary_action:
        text: "Nuestra Gobernanza"
        url: "https://www.metadocencia.org/suscripcion/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        image:
          filename: "quienessomos.jpg"
          filters:
            brightness: 0.3
        text_color_light: true   # fuerza texto claro (blanco) sobre la imagen

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Vamos por 5 años más"
          text: "Durante nuestros primeros 5 años tejimos lazos entre más de 2,000 profesionales de ciencia y técnica. Lo hicimos trabajando en equipo, de manera colectiva y colaborando con más de 40 comunidades. Gracias por estos primeros 5 años de aprendizaje, colaboración y crecimiento. ¡Vamos por 5 años más!"
          image: "quienessomos.jpg"
          button:
            text: "Conócenos"
            url: "https://hugoblox.com/templates/"
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: ["3rem", 0, "3rem", 0]   # ↓ menos padding

  - block: stats
    content:
      items:
        - statistic: "+1,000"
          description: |
            personas en Slack
        - statistic: "+40"
          description: |
            socios y patrocinadores
        - statistic: "88"
          description: |
            personas contribuyen a nuestro trabajo
        - statistic: "+6000"
          description: |
            personas conectadas en redes sociales
        - statistic: "+2600"
          description: |
            personas suscriptas a nuestro boletín
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: ["4rem", 0, "4rem", 0]   # ↓ antes estaba en 10rem

  # --- AUSPICIANTES (desplegable con lista) ---
  - block: accordion
    id: auspiciantes
    content:
      title: "Auspiciantes"
      items:
        - title: "Auspiciantes"
          content: |
            - [Nombre de auspiciante 1](#)
            - [Nombre de auspiciante 2](#)
            - [Nombre de auspiciante 3](#)
    design:
      css_class: "bg-gray-50 dark:bg-gray-800"
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  # --- COMUNIDADES AMIGAS (desplegable con lista) ---
  - block: accordion
    id: comunidades-amigas
    content:
      title: "Comunidades Amigas"
      items:
        - title: "Comunidades Amigas"
          content: |
            - [Comunidad 1](#)
            - [Comunidad 2](#)
            - [Comunidad 3](#)
    design:
      css_class: "bg-gray-50 dark:bg-gray-800"
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  # --- CONSEJO ASESOR (desplegable de personas) ---
  - block: people
    id: consejo-asesor
    content:
      title: "Consejo Asesor"
      text: "Personas que acompañan estratégicamente a MetaDocencia."
      user_groups: ["Consejo Asesor"]
      start_open: false
    design:
      columns: 4
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  # --- EQUIPO (desplegable de personas) ---
  - block: people
    id: equipo
    content:
      title: "Equipo"
      text: "Conoce al equipo que impulsa el día a día de MetaDocencia."
      user_groups: ["Equipo"]
      start_open: false
    design:
      columns: 4
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "3 TESTIMONIOS A DEFINIR - Julio Zetter"
          role: "Coordinador en Jefe de la base de datos y hemeroteca virtual SciELO México"
          image: "juliozetter.jpeg"
          text: "No cabe más que agradecer a los instructores que hicieron posible este curso, que sin duda es la semilla de grandes frutos. Gracias por tanto MetaDocencia"
    design:
      spacing:
        padding: ["3rem", 0, 0, 0]

  - block: cta-card
    content:
      title: "Apoya a la ciencia latinoamericana"
      text: "Aquí te contamos cómo"
      button:
        text: "Súmate"
        url: "https://hugoblox.com/templates/"
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
      spacing:
        padding: ["3rem", 0, "3rem", 0]
---
