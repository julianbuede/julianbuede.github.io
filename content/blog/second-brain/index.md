---
title: "Home"
type: landing

design:
  spacing: "3rem"   # menos espacio global entre secciones

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
        text_color_light: true

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Vamos por 5 años más"
          text: "Durante nuestros primeros 5 años tejimos lazos entre más de 2,000 profesionales de ciencia y técnica. Lo hicimos trabajando en equipo, de manera colectiva y colaborando con más de 40 comunidades. Gracias por estos primeros 5 años de aprendizaje, colaboración y crecimiento. ¡Vamos por 5 años más!"
          video_url: "https://youtu.be/Mcq0-4cyGKQ"   # ← reemplaza imagen por video
          button:
            text: "Conócenos"
            url: "https://hugoblox.com/templates/"
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

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
        pad
