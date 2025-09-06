---
title: "Home"
type: landing

design:
  spacing: "6rem"
  
sections:
  - block: hero
    content:
      title: Quiénes somos
      text: MetaDocencia es una organización sin fines de lucro fundada en 2020. Nuestra comunidad construye capacidades científicas locales para transformar la ciencia global. Hacemos crecer la ciencia en red, desde América Latina hacia el mundo.
    primary_action:
        text: Nuestra Gobernanza
        url: https://hugoblox.com/templates/](https://www.metadocencia.org/suscripcion/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        image:
          filename: quienessomos.jpg
          filters:
            brightness: 0.3
        text_color_light: true

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Vamos por 5 años más
          text: Durante nuestros primeros 5 años tejimos lazos entre más de 2,000 profesionales de ciencia y técnica. Lo hicimos trabajando en equipo, de manera colectiva y colaborando con más de 40 comunidades. Gracias por estos primeros 5 años de aprendizaje, colaboración y crecimiento. ¡Vamos por 5 años más!
          # Upload image to `assets/media/` and reference the filename here
          image: quienesomos.jpg
          button:
            text: Conócenos
            url: https://hugoblox.com/templates/
    design:
      # Section background color (CSS class)
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
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, "1rem", 0, "1rem"]

  - block: markdown
    id: solutions
    content:
      title: ""
      text: |
{{< spoiler text="👉 Click to view the solution" >}}
You found me!
{{< /spoiler >}}
    design:
      background:
        color: "#f6f7fb"

  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "3 TESTIMONIOS A DEFINIR - Julio Zetter"
          role: " Coordinador en Jefe de la base de datos y hemeroteca virtual SciELO México"
          # Upload image to `assets/media/` and reference the filename here
          image: "juliozetter.jpeg"
          text: "No cabe más que agradecer a los instructores que hicieron posible este curso, que sin duda es la semilla de grandes frutos. Gracias por tanto MetaDocencia"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Apoya a la ciencia latinoamericana
      text: Aquí te contamos cómo
      button:
        text: Súmate
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
