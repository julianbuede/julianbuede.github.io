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
          icon: "server"
          icon_pack: "hero"
          description: |
            Promovemos infraestructura científica y tecnológica que soporta la producción, gestión y reutilización de conocimiento.  
            <a href="/que-hacemos/infraestructura/" class="btn btn-primary mt-3 inline-block">Ver más</a>
        - name: "Formamos capacidades"
          icon: "academic-cap"
          icon_pack: "hero"
          description: |
            Creamos programas de aprendizaje colaborativo y basados en evidencia, que convierten conocimientos en acción, impulsando una investigación más abierta, eficiente y sostenible.  
            <a href="/que-hacemos/formacion/" class="btn btn-primary mt-3 inline-block">Ver más</a>
        - name: "Construimos comunidad"
          icon: "user-group"
          icon_pack: "hero"
          description: |
            Fomentamos redes de apoyo y colaboración que trascienden disciplinas, instituciones y países, para crecer y potenciar la ciencia desde América Latina hacia el mundo.  
            <a href="/que-hacemos/comunidad/" class="btn btn-primary mt-3 inline-block">Ver más</a>
    design:
      columns: 3
      css_class: "text-gray-900 dark:text-gray-100"

  # Heading centrado
  - block: cta-card
    id: heading-proyectos
    content:
      title: "Conocé nuestros proyectos"
      text: ""
    design:
      card:
        css_class: "bg-transparent shadow-none text-center"

  # ======================
  #  SECCIÓN: INFRAESTRUCTURA (AZUL)
  # ======================
  - block: cta-card
    id: infra
    content:
      title: "Impulsamos Infraestructura"
      text: "Promovemos infraestructura abierta, sostenible y orientada al reuso, para acelerar la producción y circulación del conocimiento."
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#00506F;color:#FFFFFF;"

  - block: stats
    content:
      items:
        - statistic: "3"
          description: "servicios/infraestructuras operando"
        - statistic: "12"
          description: "integraciones/automatizaciones"
        - statistic: "99.9%"
          description: "uptime en los últimos 12 meses"
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Testimonio 1"
          role: "Organización/Proyecto"
          text: "La infraestructura nos permitió escalar y compartir datos de forma abierta."
        - name: "Testimonio 2"
          role: "Investigadora/Equipo"
          text: "Estándares y procesos nos ahorraron tiempo y mejoraron la calidad."
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: features
    id: infra-proyectos
    content:
      title: "Proyectos de Infraestructura"
      text: ""
      items:
        - name: "Catalyst"
          description: "Mejoramos la accesibilidad y la utilidad de la infraestructura en la nube para comunidades globales."
        - name: "Contextualización"
          description: "Desarrollamos recursos de calidad en español a partir de material originalmente publicado en otro idioma."
        - name: "Ciencia Abierta y Datos Abiertos en la comunidad latinoamericana de bioimagen"
          description: "Proyecto a incubar"
    design:
      columns: 3

  # ======================
  #  SECCIÓN: FORMACIÓN (ROJO)
  # ======================
  - block: cta-card
    id: formacion
    content:
      title: "Formamos capacidades"
      text: "Diseñamos experiencias de aprendizaje basadas en evidencia, centradas en la práctica y con foco en el impacto."
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#C83737;color:#FFFFFF;"

  - block: stats
    content:
      items:
        - statistic: "+2,000"
          description: "personas formadas"
        - statistic: "40+"
          description: "comunidades y organizaciones aliadas"
        - statistic: "85%"
          description: "aplica lo aprendido en < 3 meses"
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Participante 1"
          role: "Curso X"
          text: "Contenidos claros y aplicables; comunidad muy activa."
        - name: "Participante 2"
          role: "Programa Y"
          text: "Aprendí herramientas y las apliqué en mi proyecto en semanas."
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
  #  SECCIÓN: COMUNIDAD (NARANJA)
  # ======================
  - block: cta-card
    id: comunidad
    content:
      title: "Construimos comunidad"
      text: "Facilitamos redes de colaboración que conectan disciplinas, instituciones y países, desde y para América Latina."
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#F77B20;color:#FFFFFF;"

  - block: stats
    content:
      items:
        - statistic: "+1,000"
          description: "personas en Slack"
        - statistic: "88"
          description: "personas contribuyentes"
        - statistic: "+40"
          description: "socios y patrocinadores"
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  - block: testimonials
    content:
      items:
        - name: "Miembro de la comunidad"
          role: "Red/Equipo"
          text: "Encontré apoyo y colaboración para avanzar en mi línea de trabajo."
        - name: "Aliada/o"
          role: "Institución"
          text: "Las alianzas nos ayudaron a amplificar el impacto regional."
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: features
    id: comunidad-proyectos
    content:
      title: "Proyectos de Comunidad"
      text: ""
      items:
        - name: "Gobernanza"
          description: "Brindamos herramientas y asesoramiento en gobernanza para que personas y organizaciones logren mayor impacto y eficiencia."
        - name: "Conversatorios"
          description: "Organizamos conversatorios y espacios de diálogo para explorar, aprender y compartir conocimiento. Fomentamos la participación y el intercambio de experiencias para fortalecer redes de colaboración y el conocimiento compartido."
        - name: "Mapeo de Ciencia Abierta en Latinoamérica"
          description: "Proyecto a incubar"
    design:
      columns: 3
---
