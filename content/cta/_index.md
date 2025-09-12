---
title: "Súmate y apoya a nuestra comunidad"
type: landing
slug: "cta"
design:
  spacing: "3rem"

sections:
  # ---------- Intro compacta ----------
  - block: cta-image-paragraph
    id: intro
    content:
      items:
        - title: "Súmate y apoya a nuestra comunidad"
          text: "Suscribite al boletín, unite a Slack, conectá con comunidades amigas y apoyá a MetaDocencia. Crecemos la ciencia en red, con recursos abiertos y formación gratuita."
          image: "quienessomos.jpg"   # imagen existente en assets/media/
    design:
      css_class: "bg-gray-50 text-gray-900 dark:bg-gray-900 dark:text-gray-100"

  # ---------- Boletín (roja con letras blancas) ----------
  - block: cta-card
    id: boletin
    content:
      title: "Boletín MetaDocencia"
      text: "Recibí en tu correo nuestras novedades, propuestas de formación, oportunidades y eventos de interés. **[Ver ediciones anteriores](https://www.metadocencia.org/boletines/)**"
      button:
        text: "Suscribite acá: Formulario de suscripción"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        css_class: "bg-red-600 text-white shadow-sm dark:bg-red-700 dark:text-white"

  # ---------- Slack (funcional, 1 botón + link en el texto) ----------
  - block: cta-card
    id: slack
    content:
      title: "Sumate a nuestro Slack"
      text: "Conectá con más de **+1000 personas** que comparten interés por la educación, la ciencia abierta y la colaboración. **[Qué es Slack y cómo puedo sumarme a la conversación](https://zenodo.org/records/10028136)**"
      button:
        text: "Unirme al espacio de Slack de MetaDocencia"
        url: "https://w3id.org/metadocencia/slack"
    design:
      card:
        css_class: "bg-white text-gray-900 shadow-sm dark:bg-gray-800 dark:text-gray-100"

  # ---------- Comunidades amigas (funcional, sin logos obligatorios) ----------
  - block: cta-card
    id: comunidades
    content:
      title: "Comunidades amigas"
      text: "Amplificamos el trabajo de organizaciones que hacen de la ciencia abierta un esfuerzo global, colectivo y comunitario."
      button:
        text: "Sumá tu comunidad"
        url: "mailto:info@metadocencia.org?subject=Sumar%20mi%20comunidad"
    design:
      card:
        css_class: "bg-gray-50 text-gray-900 shadow-sm dark:bg-gray-900 dark:text-gray-100"

  # ---------- Auspiciantes / Apoya (funcional, sin logos obligatorios) ----------
  - block: cta-card
    id: auspiciantes
    content:
      title: "Apoya a MetaDocencia"
      text: "Nuestro trabajo es posible gracias al apoyo de instituciones y organizaciones que comparten nuestra misión."
      button:
        text: "Acompañanos"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        css_class: "bg-white text-gray-900 shadow-sm dark:bg-gray-800 dark:text-gray-100"

  # ---------- Doná (solo botón, estilo primario = azul en la mayoría de temas) ----------
  - block: cta-card
    id: dona
    content:
      title: ""
      text: ""
      button:
        text: "Doná — Formulario de donación"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        css_class: "bg-transparent border-0 shadow-none p-0 text-gray-900 dark:text-gray-100"

  # ---------- Redes (nativo, sin íconos locales) ----------
  - block: features
    id: redes
    content:
      title: "Seguí la conversación"
      text: "@metadocencia · Sumate al intercambio en redes sociales."
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
      css_class: "text-gray-900 dark:text-gray-100"
---
