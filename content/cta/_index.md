---
title: "Súmate y apoya a nuestra comunidad"
type: landing
slug: "cta"
design:
  spacing: "3rem"

sections:
  # Intro compacta (solo texto e imagen, SIN CTAs)
  - block: cta-image-paragraph
    id: intro
    content:
      items:
        - title: "Súmate y apoya a nuestra comunidad"
          text: "Suscribite al boletín, unite a Slack, conectá con comunidades amigas y apoyá a MetaDocencia. Crecemos la ciencia en red, con recursos abiertos y formación gratuita."
          image: "quienessomos.jpg"   # imagen que ya tenés en assets/media/
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  # Boletín
  - block: cta-card
    id: boletin
    content:
      title: "Boletín MetaDocencia"
      text: "Recibí novedades, propuestas de formación, oportunidades y eventos de interés. **[Ver ediciones anteriores](https://www.metadocencia.org/boletines/)**"
      button:
        text: "Formulario de suscripción"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        css_class: "bg-white dark:bg-gray-900 shadow-sm"

  # Slack (2 botones) – usa tu partial comunitario cta-duo
  - block: cta-duo
    id: slack
    content:
      title: "Sumate a nuestro Slack"
      text: "Conectá con más de **+1000 personas** que comparten interés por la educación, la ciencia abierta y la colaboración."
      primary_button:
        text: "Unirme al Slack de MetaDocencia"
        url: "https://w3id.org/metadocencia/slack"
      secondary_button:
        text: "Cómo sumarme"
        url: "https://zenodo.org/records/10028136"

  # Comunidades amigas – usa split-logos (comunitario)
  - block: split-logos
    id: comunidades
    content:
      title: "Comunidades amigas"
      text: "Amplificamos el trabajo de organizaciones que hacen de la ciencia abierta un esfuerzo global, colectivo y comunitario."
      logos:
        - { src: "/media/logos/comunidades/logo1.png", alt: "Comunidad 1", url: "#" }
        - { src: "/media/logos/comunidades/logo2.png", alt: "Comunidad 2", url: "#" }
        - { src: "/media/logos/comunidades/logo3.png", alt: "Comunidad 3", url: "#" }
        - { src: "/media/logos/comunidades/logo4.png", alt: "Comunidad 4", url: "#" }
        - { src: "/media/logos/comunidades/logo5.png", alt: "Comunidad 5", url: "#" }
        - { src: "/media/logos/comunidades/logo6.png", alt: "Comunidad 6", url: "#" }
      primary_button:
        text: "Sumá tu comunidad"
        url: "https://www.metadocencia.org/contacto/"
      secondary_button:
        text: "Contacto"
        url: "https://www.metadocencia.org/contacto/"
    design:
      reverse: false
      compact: true
      css_class: "bg-gray-50 dark:bg-gray-900"

  # Auspiciantes – usa split-logos (comunitario)
  - block: split-logos
    id: auspiciantes
    content:
      title: "Apoya a MetaDocencia"
      text: "Nuestro trabajo es posible gracias al apoyo de instituciones y organizaciones que comparten nuestra misión."
      logos:
        - { src: "/media/logos/auspiciantes/logo1.png", alt: "Organización 1", url: "#" }
        - { src: "/media/logos/auspiciantes/logo2.png", alt: "Organización 2", url: "#" }
        - { src: "/media/logos/auspiciantes/logo3.png", alt: "Organización 3", url: "#" }
        - { src: "/media/logos/auspiciantes/logo4.png", alt: "Organización 4", url: "#" }
        - { src: "/media/logos/auspiciantes/logo5.png", alt: "Organización 5", url: "#" }
        - { src: "/media/logos/auspiciantes/logo6.png", alt: "Organización 6", url: "#" }
      primary_button:
        text: "Acompañanos"
        url: "https://www.metadocencia.org/contacto/"
    design:
      reverse: true
      compact: true

  # Donar (menos protagonismo)
  - block: cta-card
    id: dona
    content:
      title: "Doná"
      text: "Tu contribución nos ayuda a seguir ofreciendo **formación gratuita**, generando **recursos abiertos** y fortaleciendo la **comunidad**."
      button:
        text: "Formulario de donación"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        css_class: "bg-white dark:bg-gray-900 border border-gray-200 shadow-none"

  # Redes (nativo, sin íconos locales)
  - block: features
    id: redes
    content:
      title: ""
      items:
        - name: "X (Twitter) →"
          link: "https://twitter.com/metadocencia"
        - name: "LinkedIn →"
          link: "https://www.linkedin.com/company/metadocencia/"
        - name: "YouTube →"
          link: "https://www.youtube.com/@metadocencia"
        - name: "Instagram →"
          link: "https://www.instagram.com/metadocencia/"
        - name: "Mastodon →"
          link: "https://mastodon.social/@metadocencia"
    design:
      columns: 5
---
