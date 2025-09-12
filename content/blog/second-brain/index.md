---
title: "Second Brain"
type: landing

design:
  spacing: "3rem"

sections:
  - block: hero
    content:
      title: "Second Brain"
      text: "Una mirada a nuestras prácticas y aprendizajes."
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        color: "gray-900"
        text_color_light: true

  # Bloque con IMAGEN (reemplaza al de video)
  - block: cta-image-paragraph
    id: intro
    content:
      items:
        - title: "Vamos por 5 años más"
          text: "Durante nuestros primeros 5 años tejimos lazos entre más de 2,000 profesionales de ciencia y técnica. Lo hicimos trabajando en equipo, de manera colectiva y colaborando con más de 40 comunidades."
          image: "quienessomos.jpg"   # <-- debe existir en assets/media/
          button:
            text: "Conócenos"
            url: "https://www.metadocencia.org/suscripcion/"
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
