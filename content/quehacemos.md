---
title: "Qué hacemos"
type: landing
slug: "que-hacemos"
design:
  spacing: "3rem"

sections:
  # Intro (imagen + texto)
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Qué hacemos"
          text: "Potenciamos el ecosistema científico latinoamericano con infraestructura, formación y comunidad."
          image: "organigramaapaisado.png"  # asegurate de tenerla en assets/media/
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

  # Tres columnas con iconos + CTA "Ver más"
  - block: features
    id: pilares
    content:
      title: ""
      text: ""
      items:
        - name: "Impulsamos Infraestructura"
          icon: "server"          # Heroicons → assets/media/icons/hero/server.svg
          icon_pack: "hero"
          description: |
            Promovemos infraestructura científica y tecnológica que soporta la producción, gestión y reutilización de conocimiento.  
            <a href="/que-hacemos/infraestructura/" class="btn btn-primary mt-3 inline-block">Ver más</a>
        - name: "Formamos capacidades"
          icon: "academic-cap"    # Heroicons → assets/media/icons/hero/academic-cap.svg
          icon_pack: "hero"
          description: |
            Creamos programas de aprendizaje colaborativo y basados en evidencia, que convierten conocimientos en acción, impulsando una investigación más abierta, eficiente y sostenible.  
            <a href="/que-hacemos/formacion/" class="btn btn-primary mt-3 inline-block">Ver más</a>
        - name: "Construimos comunidad"
          icon: "user-group"      # Heroicons → assets/media/icons/hero/user-group.svg
          icon_pack: "hero"
          description: |
            Fomentamos redes de apoyo y colaboración que trascienden disciplinas, instituciones y países, para crecer y potenciar la ciencia desde América Latina hacia el mundo.  
            <a href="/que-hacemos/comunidad/" class="btn btn-primary mt-3 inline-block">Ver más</a>
    design:
      columns: 3
      css_class: "text-gray-900 dark:text-gray-100"

  # Heading centrado: "Conocé nuestros proyectos"
  - block: cta-card
    id: heading-proyectos
    content:
      title: "Conocé nuestros proyectos"
      text: ""
    design:
      card:
        css_class: "bg-transparent shadow-none text-center"
        css_style: ""

  # ======================
  #  SECCIÓN: INFRAESTRUCTURA
  # ======================
  - block: cta-card
    id: infra
    content:
      title: "Impulsamos Infraestructura"
      text: "Promovemos infraestructura abierta, sostenible y orientada al reuso, para acelerar la producción y circulación del conocimiento."
    design:
      card:
        css_class: "bg-white text-gray-900 dark:bg-gray-800 dark:text-gray-100 shadow-sm"

  - block: stats
    content:
      items:
        - statistic: "3"
          description: "servicios/infraestructuras operando"   # ← reemplazar
        - statistic: "12"
          description: "integraciones/automatizaciones"         # ← reemplazar
        - statistic: "99.9%"
          description: "uptime en los últimos 12 meses"         # ← reemplazar
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Testimonio 1"
          role: "Organización/Proyecto"
          text: "La infraestructura nos permitió escalar y compartir datos de forma abierta."  # ← reemplazar
        - name: "Testimonio 2"
          role: "Investigadora/Equipo"
          text: "Estándares y procesos nos ahorraron tiempo y mejoraron la calidad."          # ← reemplazar
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: features
    id: infra-proyectos
    content:
      title: "Proyectos de Infraestructura"
      text: ""
      items:
        - name: "Catálogo de recursos abiertos"
          description: "Indexa y mantiene actualizado material formativo y datasets reutilizables."   # ← reemplazar
        - name: "Automatización de flujos"
          description: "Pipelines reproducibles para publicación y actualización de contenidos."      # ← reemplazar
        - name: "Interoperabilidad y estándares"
          description: "Políticas de metadatos y esquemas para mejorar búsqueda y reuso."            # ← reemplazar
    design:
      columns: 3

  # ======================
  #  SECCIÓN: FORMACIÓN
  # ======================
  - block: cta-card
    id: formacion
    content:
      title: "Formamos capacidades"
      text: "Diseñamos experiencias de aprendizaje basadas en evidencia, centradas en la práctica y con foco en el impacto."
    design:
      card:
        css_class: "bg-white text-gray-900 dark:bg-gray-800 dark:text-gray-100 shadow-sm"

  - block: stats
    content:
      items:
        - statistic: "+2,000"
          description: "personas formadas"                    # ← reemplazar si deseas
        - statistic: "40+"
          description: "comunidades y organizaciones aliadas" # ← reemplazar
        - statistic: "85%"
          description: "aplica lo aprendido en < 3 meses"     # ← reemplazar
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Participante 1"
          role: "Curso X"
          text: "Contenidos claros y aplicables; comunidad muy activa."  # ← reemplazar
        - name: "Participante 2"
          role: "Programa Y"
          text: "Aprendí herramientas y las apliqué en mi proyecto en semanas."  # ← reemplazar
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: features
    id: formacion-proyectos
    content:
      title: "Proyectos de Formación"
      text: ""
      items:
        - name: "Formación en Ciencia Abierta"
          description: "Talleres y recursos para abrir, compartir y reutilizar conocimiento."
        - name: "Financiamiento"
          description: "Herramientas para identificar, postular y gestionar oportunidades."
        - name: "Formación para Formar"
          description: "Programa para multiplicar capacidades de enseñanza y mentoría."
    design:
      columns: 3

  # ======================
  #  SECCIÓN: COMUNIDAD
  # ======================
  - block: cta-card
    id: comunidad
    content:
      title: "Construimos comunidad"
      text: "Facilitamos redes de colaboración que conectan disciplinas, instituciones y países, desde y para América Latina."
    design:
      card:
        css_class: "bg-white text-gray-900 dark:bg-gray-800 dark:text-gray-100 shadow-sm"

  - block: stats
    content:
      items:
        - statistic: "+1,000"
          description: "personas en Slack"     # ← reemplazar
        - statistic: "88"
          description: "personas contribuyentes" # ← reemplazar
        - statistic: "+40"
          description: "socios y patrocinadores" # ← reemplazar
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Miembro de la comunidad"
          role: "Red/Equipo"
          text: "Encontré apoyo y colaboración para avanzar en mi línea de trabajo." # ← reemplazar
        - name: "Aliada/o"
          role: "Institución"
          text: "Las alianzas nos ayudaron a amplificar el impacto regional."       # ← reemplazar
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: features
    id: comunidad-proyectos
    content:
      title: "Proyectos de Comunidad"
      text: ""
      items:
        - name: "Encuentros y co-creación"
          description: "Sesiones abiertas, grupos de trabajo y espacios de intercambio."   # ← reemplazar
        - name: "Programa de colaboraciones"
          description: "Articulación con comunidades y equipos para iniciativas conjuntas." # ← reemplazar
        - name: "Difusión y recursos comunitarios"
          description: "Boletín, repositorios y guías vivas para toda la red."             # ← reemplazar
    design:
      columns: 3
---
