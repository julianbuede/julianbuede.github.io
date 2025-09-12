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
      # Fondo muy claro (oscuro en dark) + texto con alto contraste
      css_class: "bg-gray-50 text-gray-900 dark:bg-gray-900 dark:text-gray-100"

  # ---------- Boletín (card legible) ----------
  - block: cta-card
    id: boletin
    content:
      title: "Boletín MetaDocencia"
      text: "Recibí en tu correo nuestras novedades, propuestas de formación, oportunidades y eventos de interés. **[Ver ediciones anteriores](https://www.metadocencia.org/boletines/)**"
      button:
        text: "Formulario de suscripción"
        url: "https://www.metadocencia.org/contacto/"
    design:
      card:
        # Card clara (oscura en dark) + texto contrastado
        css_class: "bg-white text-gray-900 shadow-sm dark:bg-gray-800 dark:text-gray-100"

  # ---------- Slack (2 botones) ----------
  - block: cta-duo
    id: slack
    content:
      title: "Sumate a nuestro Slack"
      text: "Conectá con más de **+1000 personas** que comparten interés por la educación, la ciencia abierta y la colaboración."
      primary_button:
        text: "Unirme al espacio de Slack de MetaDocencia"
        url: "https://w3id.org/metadocencia/slack"
      secondary_button:
        text: "Qué es Slack y cómo sumarme"
        url: "https://zenodo.org/records/10028136"
    design:
      # Nuestro partial aplica bg blanco por defecto; reforzamos contraste del texto
      css_class: "text-gray-900 dark:text-gray-100"

  # ---------- Comunidades amigas (split 2 columnas) ----------
  - block: split-logos
    id: comunidades
    content:
      title: "Comunidades amigas"
      text: "Amplificamos el trabajo de organizaciones que hacen de la ciencia abierta un esfuerzo global, colectivo y comunitario."
      logos: []   # mostrará el texto/botones aunque no haya logos aún
      primary_button:
        text: "Sumá tu comunidad"
        url: "mailto:info@metadocencia.org?subject=Sumar%20mi%20comunidad"
      secondary_button:
        text: "Contacto"
        url: "https://www.metadocencia.org/contacto/"
    design:
      reverse: false
      compact: true
      # Fondo blanco (gris muy oscuro en dark) + texto contrastado
      css_class: "bg-white text-gray-900 dark:bg-gray-900 dark:text-gray-100"

  # ---------- Auspiciantes / Apoya (split 2 columnas) ----------
  - block: split-logos
    id: auspiciantes
    content:
      title: "Apoya a MetaDocencia"
      text: "Nuestro trabajo es posible gracias al apoyo de instituciones y organizaciones que comparten nuestra misión."
      logos: []   # mostrará texto/botón aunque no haya logos aún
      primary_button:
        text: "Acompañanos"
        url: "https://www.metadocencia.org/contacto/"
    design:
      reverse: true
      compact: true
      # Alternamos fondo para ritmo visual
      css_class: "bg-gray-50 text-gray-900 dark:bg-gray-800 dark:text-gray-100"

  # ---------- Donar (bajísimo protagonismo: solo botón suelto) ----------
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
        # Transparente y sin sombra, pero con texto legible
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
      # Texto siempre legible
      css_class: "text-gray-900 dark:text-gray-100"
---
