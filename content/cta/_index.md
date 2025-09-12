---
title: "Súmate y apoya a nuestra comunidad"
type: landing
slug: "cta"
design:
  spacing: "3rem"

sections:
  # --------- Intro concisa (sin hero grande) ----------
  - block: cta-duo
    id: intro
    content:
      title: "Súmate y apoya a nuestra comunidad"
      text: "Suscribite al boletín, unite a Slack, conectá con comunidades amigas y apoyá a MetaDocencia."
      primary_button:
        text: "Suscribirme al boletín"
        url: "https://www.metadocencia.org/contacto/"
      secondary_button:
        text: "Unirme al Slack"
        url: "https://w3id.org/metadocencia/slack"
    design:
      css_class: ""

  # --------- Boletín ----------
  - block: cta-duo
    id: boletin
    content:
      title: "Boletín MetaDocencia"
      text: "Recibí en tu correo nuestras novedades, propuestas de formación, oportunidades y eventos de interés."
      primary_button:
        text: "Formulario de suscripción"
        url: "https://www.metadocencia.org/contacto/"
      secondary_button:
        text: "Ver ediciones anteriores"
        url: "https://www.metadocencia.org/boletines/"

  # --------- Slack (con botón de 'cómo sumarme') ----------
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

  # --------- Comunidades amigas (split logos) ----------
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
        url: "mailto:info@metadocencia.org?subject=Sumar%20mi%20comunidad"
      secondary_button:
        text: "Contacto"
        url: "https://www.metadocencia.org/contacto/"
    design:
      reverse: false     # poné true si querés texto a la izquierda y logos a la derecha
      compact: true

  # --------- Auspiciantes / Apoya (split logos) ----------
  - block: split-logos
    id: auspiciantes
    content:
      title: "Apoya a MetaDocencia"
      text: "Nuestro trabajo es posible gracias al apoyo de instituciones y organizaciones que comparten nuestra misión."
      logos:
        - { src: "/media/logos/auspiciantes/logo1.png", alt: "Org 1", url: "#" }
        - { src: "/media/logos/auspiciantes/logo2.png", alt: "Org 2", url: "#" }
        - { src: "/media/logos/auspiciantes/logo3.png", alt: "Org 3", url: "#" }
        - { src: "/media/logos/auspiciantes/logo4.png", alt: "Org 4", url: "#" }
        - { src: "/media/logos/auspiciantes/logo5.png", alt: "Org 5", url: "#" }
        - { src: "/media/logos/auspiciantes/logo6.png", alt: "Org 6", url: "#" }
      primary_button:
        text: "Acompañanos"
        url: "https://www.metadocencia.org/contacto/"
    design:
      reverse: true      # logos a la derecha, texto a la izquierda
      compact: true

  # --------- Donar ----------
  - block: cta-duo
    id: dona
    content:
      title: "Doná"
      text: "Tu contribución nos ayuda a seguir ofreciendo **formación gratuita**, generando **recursos abiertos** y fortaleciendo la **comunidad**."
      primary_button:
        text: "Formulario de donación"
        url: "https://www.metadocencia.org/contacto/"   # reemplazá si tenés otra URL

  # --------- Redes: solo íconos pequeños ----------
  - block: social-icons
    id: redes
    content:
      items:
        - { url: "https://twitter.com/metadocencia",  image: "/media/icons/x.svg",         alt: "X (Twitter)" }
        - { url: "https://www.linkedin.com/company/metadocencia/", image: "/media/icons/linkedin.svg", alt: "LinkedIn" }
        - { url: "https://www.youtube.com/@metadocencia", image: "/media/icons/youtube.svg",  alt: "YouTube" }
        - { url: "https://www.instagram.com/metadocencia/", image: "/media/icons/instagram.svg", alt: "Instagram" }
        - { url: "https://mastodon.social/@metadocencia", image: "/media/icons/mastodon.svg", alt: "Mastodon" }
---
