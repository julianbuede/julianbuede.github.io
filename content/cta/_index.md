---
title: "Súmate y apoya a nuestra comunidad"
type: landing
slug: "cta"
design:
  spacing: "3rem"

sections:
  # ---------- Intro compacta  ----------
  - block: cta-image-paragraph
    id: intro
    content:
      items:
        - title: "Súmate y apoya a nuestra comunidad"
          text: "Suscribite al boletín, unite a Slack, conectá con comunidades amigas y apoyá a MetaDocencia. Crecemos la ciencia en red, con recursos abiertos y formación gratuita."
          image: "quienessomos.jpg"   # usa una imagen que ya existe en assets/media/
    design:
      css_class: "bg-gray-50 dark:bg-gray-900 text-gray-900 dark:text-gray-100"

  # ---------- Boletín (card legible sobre blanco) ----------
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
        css_class: "bg-white dark:bg-gray-900 text-gray-900 dark:text-gray-100 shadow-sm"

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
      css_class: "text-gray-900 dark:text-gray-100"

  # ---------- Comunidades amigas (split 2 columnas: logos izq — texto der) ----------
  - block: split-logos
    id: comunidades
    content:
      title: "Comunidades amigas"
      text: "Amplificamos el trabajo de organizaciones que hacen de la ciencia abierta un esfuerzo global, colectivo y comunitario."
      logos:
        # Subí tus logos a assets/media/logos/comunidades/ y ajustá las rutas:
        - { src: "/media/logos/comunidades/logo1.png", alt: "Comunidad 1", url: "#" }
        - { src: "/media/logos/comunidades/logo2.png", alt: "Comunidad 2", url: "#" }
        - { src: "/media/logos/comunidades/logo3.png", alt: "Comunidad 3", url: "#" }
        - { src: "/media/logos/comunidades/logo4.png", alt: "Comunidad 4", url: "#" }
        - { src: "/media/logos/comunidades/logo5.png", alt: "Comunidad 5", url: "#" }
        - { src: "/media/logos/comunidades/logo6.png", alt: "Comunidad 6", url: "#" }
      primary_button:
        text: "Sumá tu comunidad"
        url: "mailto:info@metadocencia.org?subject=Sumar%20mi%20comunidad"
      secondary_button:
        text: "Contacto"
        url: "https://www.metadocencia.org/contacto/"
    design:
      reverse: false
      compact: true
      css_class: "bg-white dark:bg-gray-900 text-gray-900 dark:text-gray-100"

  # ---------- Auspiciantes / Apoya (split 2 columnas: texto izq — logos der) ----------
  - block: split-logos
    id: auspiciantes
    content:
      title: "Apoya a MetaDocencia"
      text: "Nuestro trabajo es posible gracias al apoyo de instituciones y organizaciones que comparten nuestra misión."
      logos:
        # Subí tus logos a assets/media/logos/auspiciantes/ y ajustá las rutas:
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
      css_class: "bg-gray-50 dark:bg-gray-900 text-gray-900 dark:text-gray-100"

  # ---------- Donar (muy bajo protagonismo: solo botón suelto) ----------
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
        # tarjeta casi invisible (sin fondo/sombra) y texto legible
        css_class: "bg-transparent shadow-none border-0 p-0 text-gray-900 dark:text-gray-100"

  # ---------- Redes (nativo, sin íconos locales) ----------
  - block: features
    id: redes
    content:
      title: "Seguí la conversación · @metadocencia"
      text: "Sumate al intercambio en redes sociales."
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
